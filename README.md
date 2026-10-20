# Installing Transcriber

Transcriber records a visit, writes out what was said, and drafts a SOAP note for you to review. It runs on your own computer, and recordings never leave it.

## You Need

- A Windows 10 or Windows 11 computer with 8 GB of memory or more and 6 GB of free space.
- A microphone.
- An internet connection the first time you open Transcriber.

## Install

1. Click this link to download the installer: <https://github.com/Vero-Ventures/transcriber-releases/releases/latest/download/Transcriber-win-Setup.exe>
2. Open the downloaded file. If your browser asks whether to keep it, choose **Keep**.
3. If a blue "Windows protected your PC" box appears, click **More info**, then **Run anyway**. This only happens the first time.
4. If it says "Additional Components Required", click **Install**, then **Yes**. This installs a standard Microsoft component that Transcriber needs.

That's it. Transcriber installs itself, puts a **Transcriber** icon on your desktop, and opens.

## First Launch

The first time it opens, Transcriber downloads its speech models (about 3 GB). The top-right corner of the window shows the progress. Leave it open until it finishes; on a typical connection this takes 5 to 30 minutes. If the internet drops or you close the window, it picks up where it left off the next time you open it.

## Everyday Use

1. Double-click the **Transcriber** icon on your desktop.
2. Press **Record** at the start of the visit and **Stop** at the end.
3. Check the transcript, then generate the SOAP draft, review it, and save it.

The SOAP note is a draft. You review and approve it before it goes into the medical record.

## If Something Goes Wrong

- **It can't find a microphone:** open Windows Settings, then Privacy and security, then Microphone, and turn on "Let desktop apps access your microphone".
- **Setup says it is paused:** check the internet connection. It retries on its own every 30 seconds.
- **Your antivirus blocks `whisper-cli.exe` or `llama-completion.exe`:** these are the speech and drafting engines that come with Transcriber. Allow them.
