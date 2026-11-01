# Add Your Training Profiles

**Status:** Setup instructions. Your public profile URLs have not been supplied or verified in this file.

Use your real public profile links. Your TryHackMe or Hack The Box username might differ from **Kiemar** or **KieSec**. Plain links are enough; an iframe, dynamic badge, API key, or automatic statistics integration is unnecessary.

## TryHackMe

Sign in and visit [your profile page](https://tryhackme.com/profile). Click **Public Profile** and copy the resulting public URL. Do not share the generic `/profile` dashboard address. Open the copied URL in a signed-out or private/incognito browser window and confirm that it shows the profile you intend to publish.

## Hack The Box

Open **Profile** from your HTB dashboard or visit [HTB Profile](https://profile.hackthebox.com). Review the personal information shown and set the profile visibility to **Public** if you want to share it; the documented default is private. Copy your actual public/share URL. Verify it while signed out. Do not guess a numeric or username-based URL.

## Add the links to GitHub

1. Open your `Kiemar/Kiemar` profile README and choose the pencil icon.
2. Add the snippet below where you want your training links.
3. **Replace both placeholder values with your verified URLs before committing.** If one profile is not ready, omit its entire link.
4. Preview, commit directly to `main`, and test the links from your GitHub profile.
5. Add the same links to the **Learning and training** section in `kiesec/README.md`. The homelab README does not need duplicate training statistics.

Setup snippet only; it is deliberately inside a code block so these are not broken live links:

```markdown
[TryHackMe](PASTE_PUBLIC_THM_URL) · [Hack The Box](PASTE_PUBLIC_HTB_URL)
```

Profiles show participation and progress. Your project write-ups should provide the evidence of how you reason, test, explain results, and verify improvements. Do not rely on rank or completion counts alone.

## Official references

Profile instructions checked on **31 October 2026**. Recheck the current interface if a label changes.

- [TryHackMe official guidance containing the Public Profile steps](https://help.tryhackme.com/en/articles/13367548-the-cold-start-terms-and-conditions)
- [HTB Profile official guide](https://help.hackthebox.com/en/articles/13616849-htb-profile)

[Back to KieSec](README.md)
