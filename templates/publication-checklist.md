# Template Publication Review

Use this checklist before changing a repository to public, publishing a write-up, uploading a report, or linking work from your CV. Review the full repository history as well as the latest files.

## Authority and platform rules

- [ ] I own the lab, have documented permission, or am using a dataset with an appropriate license.
- [ ] The public scope description is accurate and does not expose confidential authorization documents.
- [ ] I checked the platform's current rules for this exact machine, challenge, module, exam, or dataset.
- [ ] I recorded its publication status and the date I checked it; a machine's **Expired** status is not its **Retired** status.
- [ ] I did not assume that removing a flag or answer makes a prohibited active-lab solution publishable.
- [ ] I credited permitted third-party material and have rights to include it.

### Platform references checked on 31 October 2026

Recheck these official pages immediately before publishing; rules and content status can change.

- **TryHackMe:** [Acceptable Use Policy](https://tryhackme.com/legal/acceptable-use-policy). Active solutions are prohibited under the checked policy; content without a retirement designation defaults to active. Follow the platform's guidance for retired content. When uncertain, publish a concept explanation or original recreation in your own lab without exposing restricted task solutions.
- **Hack The Box:** [Streaming Writeups and Walkthrough Guidelines](https://help.hackthebox.com/en/articles/5188925-streaming-writeups-walkthrough-guidelines). Check the exact permitted category, including retired machines, challenges and Sherlocks, Starting Point, and Tier 0 Academy content under the checked guidance. A machine marked **Expired** may still be active; verify that it is officially **Retired** before treating it as retired content. Expired account access also does not establish retirement. Verify current status before publication.
- **PortSwigger Web Security Academy:** [Community video guidelines](https://portswigger.net/web-security/video-guidelines). PortSwigger explicitly welcomes original community solution videos covering individual labs and asks creators to explain why steps work. This is a supported route, not blanket permission to reproduce all course material, assessments, or exam content. Follow the relevant current terms for the format and material you publish.

## Privacy and evidence

- [ ] No passwords, API keys, tokens, private keys, personal information, or confidential employer/customer material appear in files, metadata, screenshots, URLs, logs, or history.
- [ ] Public screenshots and reports are sanitized derivatives; the private original is tracked separately when preservation is appropriate.
- [ ] Blurring or cropping did not leave recoverable text layers, hidden document content, or identifying filenames.
- [ ] Real targets and people are not unnecessarily exposed by an OSINT case study.
- [ ] The `.gitignore` exclusions were reviewed, and ignored files were not manually force-added.
- [ ] If a credential was exposed, I revoked or rotated it; deleting the visible line alone is not a remedy.

## Accuracy and ownership

- [ ] Every result described as observed has supporting evidence.
- [ ] Lab work is labeled as lab work, and planned tests are not written in the past tense.
- [ ] Dates, versions, scope, and limitations are explicit.
- [ ] Severity has a rationale; scanner labels are not presented as validated conclusions.
- [ ] I explain my own contribution and disclose walkthroughs, hints, collaborators, and AI assistance.
- [ ] I can explain the commands, code, conclusions, and fixes without reading a script.
- [ ] I distinguish infrastructure indicators from human or organizational attribution.

## Reviewer experience

- [ ] The README explains the question, contribution, outcome, and limits in about one minute.
- [ ] Links work from the actual repository paths.
- [ ] Screenshots are legible and captioned; the essential reasoning is also written as text.
- [ ] Setup and reproduction instructions were checked in the stated environment.
- [ ] The report contains remediation and retest results, or explicitly states why a retest was not performed.
- [ ] No template instruction, dummy evidence ID, example result, or placeholder URL is presented as completed work.

**Review date:** [Date] · **Reviewer:** [Name] · **Decision:** [Publish / revise / keep private]

**Open concerns:** [Specific unresolved issues]
