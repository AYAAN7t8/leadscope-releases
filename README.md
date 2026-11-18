# LeadScope for Windows

LeadScope finds recent leads (clients posting projects, companies hiring, local businesses) on public
sites with your own Chrome, at human pace, and saves them to Excel. Your data stays on your PC.

This page only hosts the installer. The source code is not published here.

## Download

Get the latest version from **[Releases](../../releases/latest)**: download `LeadScope-Setup-<version>.zip`,
unzip it and run `LeadScope-Setup-<version>.exe`.

- Windows 10 or 11, 64-bit
- Google Chrome installed
- About 900 MB of free disk space

Windows SmartScreen may say "Windows protected your PC" because the installer is not code-signed yet.
Click **More info → Run anyway** if you downloaded it from this page.

Each release lists the SHA-256 checksum of the zip so you can check your download:

```powershell
Get-FileHash .\LeadScope-Setup-0.3.2.zip -Algorithm SHA256
```

## What's new in 0.3.2

- **Facebook, Instagram, X and Telegram**: search posts with your own login, or add groups, pages and public channels. Off until you accept the risk (these platforms forbid automated reading and may limit your account).
- **Contact buttons on every lead**: Email, Call, WhatsApp, Telegram, or Reply on post. They open your own apps; LeadScope never sends messages.
- **New sources**: PeoplePerHour, and Freelancer.com (off by default, see its note in the app).
- **Fix**: 0.3.0 shipped an older engine; Schedules, own sites and Google Maps (browser) work again.
- **Schedules**: save a search to run by itself every day or on chosen weekdays; new leads go to Excel automatically.
- **Runs in the tray** and can start with Windows, so schedules run without opening the app.
- **Add your own sites**: paste any job board, project marketplace or directory page.
- **Google Maps without an API key** (reads Maps in your Chrome; see the note in the app about Google's terms).

## Using it responsibly

LeadScope checks robots.txt, keeps a human pace with daily page limits, never solves CAPTCHAs or bypasses
logins, and pauses to ask you when a site shows a check. You are responsible for following each site's
terms and data-protection law (such as GDPR) for the leads you collect.
