---
title: "SpeakEasy Privacy"
page_heading: "SpeakEasy Privacy Policy"
version: "1.2.0_2026.08.05_1606"
---

## The short version

SpeakEasy STT processes your voice **entirely on your own computer**. Your audio and the text transcribed from it are never sent to us or to any third party. SpeakEasy has no user accounts, no sign-in, and no servers that receive your content.

## Who we are

SpeakEasy STT ("SpeakEasy," "the app," "we," "us") is a speech-to-text application for Windows, published by **Affiniti Group**.

## What the app accesses on your device

- **Microphone / audio input.** When you start transcription, SpeakEasy captures audio from the microphone or input device you select. This audio is processed locally, in memory, on your device, to produce text. You control when the app is listening.
- **Speech-to-text model.** The model that converts your speech to text runs entirely and only on your computer.  It is downloaded once during setup (see *Network connections* below); after that, no Internet connection is required to transcribe your speech.

## What we collect

**Nothing.** SpeakEasy does not create an account, does not require sign-in, and does not transmit your audio, your transcripts, your settings, or any personal or usage information to Affiniti Group or to any third party. We operate no servers that receive your content, because your content never leaves your device.

## Where your data lives

**SpeakEasy does not store your dictation.** The audio you speak and the text transcribed from it are held only in your computer's memory long enough to produce the text, and are then discarded. SpeakEasy does **not** write your dictation audio to disk, does **not** save a transcript or history of what you dictate, and does **not** keep a record of the text it types for you.

The only things SpeakEasy keeps on your computer, inside your Windows user profile, are:

- **Your settings** — your preferences and shortcut choices.
- **TrueWord custom-word training samples.** If you use the TrueWord feature to teach the app a custom word or name, the short audio samples you record for that word are stored locally so the app can recognize it. These samples are used **only** to build your local custom-word recognition and are never transmitted anywhere. You can delete them at any time by removing the keyword in the app, which removes both the entry and its associated audio samples.
- **The speech-to-text model** — the model file downloaded once during setup (see *Network connections* below).
- **One local log file** used for troubleshooting. It contains **no transcribed content** — it records events and timings (for example, that a transcription of a certain length completed), never the words you dictate. It stays on your computer unless you choose to share it with us for support (see "Analytics, telemetry, and crash reporting" below).

All of this lives in one folder in your user profile: `%USERPROFILE%\.speakeasy`. Uninstalling SpeakEasy removes the app itself and leaves this folder in place, so reinstalling later restores your settings without downloading the model again. You can delete the folder yourself at any time.

## Analytics, telemetry, and crash reporting

SpeakEasy does not include third-party analytics, advertising, tracking, telemetry, or automatic crash reporting. **The app does not "phone home": it never automatically transmits your audio, transcripts, settings, diagnostic logs, or any other personal or usage information to us or to anyone else.** The local diagnostic log described above stays on your computer.

The only way your diagnostic log would ever reach us is if **you choose to send it to us** — for example, to help us investigate a problem you have reported. That is always your decision: the app does not transmit the log on its own, and if a future version offers a way to share diagnostics for support, it will do so only with your explicit consent and acknowledgement. Even then, we would use what you send solely to diagnose the issue you raised.

## Network connections

SpeakEasy transcribes entirely on your device and does not need an Internet connection to do so. It makes only these connections, none of which send your audio, transcripts, or personal information:

- **One-time model download.** On first setup, SpeakEasy downloads the speech-to-text model it uses to transcribe. The model is hosted in our own public repository at https://github.com/123t4me/speakeasy-models, and the app verifies the downloaded file against a known cryptographic hash (SHA-256) before using it. This transfers only the model file; it sends none of your data. As with any download, the connection is visible to the host (GitHub) and may include your IP address as an ordinary part of making the request.
- **App updates via the Microsoft Store.** SpeakEasy is distributed through the Microsoft Store, and updates are delivered by the Store. The Store build does not contact our own infrastructure to check for or download updates.

Apart from the one-time model download, SpeakEasy makes no network connections in the course of normal transcription use.

## Children's privacy

SpeakEasy is not directed to children and does not knowingly collect information from anyone — because it collects no personal information at all.

## Changes to this policy

We may update this policy from time to time. The Version Number at the very top of this document gets updated when any changes are made.  Material changes will be reflected in the app's Store listing.

## Contact

Questions about this policy or the app's handling of data:

**privacy@123t4me.com**
Affiniti Group
