# Example Learning Entry Understanding Bash Redirection Order

**Status:** Prepared teaching example, not a record of Kiemar's completed work. Run it yourself and record your own environment and observations before adapting it into a personal journal entry.

## The question

What does `2>&1` mean, and why can moving it change the output?

## My explanation

In Bash, file descriptor `1` is standard output and `2` is standard error. `2>&1` makes descriptor `2` refer to the same destination that descriptor `1` has **at that point**. Bash applies these redirections from left to right. It is not a permanent instruction to follow any future change to descriptor `1`.

## Safe local experiment

Run these commands in Bash. They create text files in a new temporary directory.

```bash
redirect_practice_dir=$(mktemp -d)
cd "$redirect_practice_dir"

{ printf 'out\n'; printf 'err\n' >&2; } >combined.txt 2>&1
cat combined.txt
```

Expected output from `cat`:

```text
out
err
```

First, `>combined.txt` directs standard output to the file. Then `2>&1` points standard error to that same destination. The two `printf` commands run sequentially in this example.

Now reverse the redirections:

```bash
{ printf 'out\n'; printf 'err\n' >&2; } 2>&1 >stdout-only.txt
cat stdout-only.txt
```

In an ordinary interactive terminal, the command group prints `err` to the terminal. The later `cat` prints `out`, which is the only line in the file. The first redirection copied the original standard-output destination; the second then changed only descriptor `1`.

If running inside another wrapper that already redirects standard output, `err` goes to that original destination instead of necessarily going to a terminal. The rule is about destinations, not the screen.

## Related syntax

- `2>/dev/null` discards standard error only.
- `>/dev/null 2>&1` discards both standard output and standard error.
- A normal `|` sends standard output into the next command. It does not include standard error automatically.
- In Bash, `|&` is shorthand for piping both streams, with Bash-specific redirection behavior. Learn the explicit form first.

## Why this matters

A scan or script can report useful failures on standard error. Discarding those failures may make a command look successful when it did not test what I intended. I should choose whether to preserve, inspect, or suppress them deliberately.

## Recall check

Without running it, predict where both lines go in each command above. Explain why `2>&1 >file` and `>file 2>&1` can differ.

## Assistance and verification

This explanation and experiment were supplied as a starter-kit example. A personal entry should state whether I needed help, show my own verified result, and identify what I could repeat without notes.

Primary reference: [GNU Bash manual on redirections](https://www.gnu.org/software/bash/manual/html_node/Redirections.html).

[Back to portfolio](../README.md)
