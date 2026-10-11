<p align="center">
  <img src="assets/extractaudiogpt-icon.png" width="128" alt="ExtractAudioGPT">
</p>

<h1 align="center">ExtractAudioGPT</h1>

<p align="center"><strong>Download ChatGPT audio with a single click.</strong></p>

<p align="center">
  Turn ChatGPT's Read Aloud feature into audio files you can save, listen to, and reuse whenever you want.
</p>

<p align="center">
  <a href="https://github.com/jasp402/ExtractAudioGPT/releases"><strong>Get the extension</strong></a>
  ·
  <a href="https://github.com/jasp402/ExtractAudioGPT/issues/new/choose">Get support</a>
  ·
  <a href="PRIVACY.md">Privacy policy</a>
</p>

> **Status:** Testing release. Public distribution and Chrome Web Store availability are being prepared. Full functionality has not yet been verified in Chrome.

## Your audio, your way

| Feature | What you can do |
| --- | --- |
| **One-click downloads** | Use the button next to **Read Aloud** to save the audio from a ChatGPT response. |
| **Automatic downloads** | Turn **YES** on to automatically download newly played audio when captured. |
| **Optional MP3 conversion** | Convert captured audio to MP3 locally for broader device compatibility. |
| **Keep the original format** | Turn MP3 conversion off to save the received audio without re-encoding. |
| **Stay in control** | Set automatic downloads to **NO** while keeping manual downloads available. |

**Your audio is not uploaded to our servers.** Processing and conversion happen in your browser, and Chrome handles file downloads. Settings are stored using `chrome.storage.sync`.

## Getting started

To install the current release manually:

1. Download **ExtractAudioGPT.zip** from the [latest GitHub Release](https://github.com/jasp402/ExtractAudioGPT/releases) and extract it. Do not use GitHub's auto-generated **Source code (zip)** archive.
2. Open `chrome://extensions` in Chrome and enable **Developer mode**.
3. Click **Load unpacked** and select the folder containing `manifest.json`.
4. Visit `https://chatgpt.com/` and play a response using **Read Aloud**.
5. Click the download button next to the response, or open the extension popup and choose **YES** to enable automatic downloads.

Downloaded files are saved to `Downloads/ExtractAudioGPT`. If MP3 conversion fails, the extension saves the original audio format instead.

## Need help?

Is a download missing, MP3 conversion failing, or has ChatGPT changed its interface? **Open a GitHub Issue** and tell us what happened.

**[Report a bug or request a feature →](https://github.com/jasp402/ExtractAudioGPT/issues/new/choose)**

Please include your extension version, Chrome version, and steps to reproduce the issue. **Do not share private conversations, cookies, or session tokens.**

## Privacy and transparency

ExtractAudioGPT is designed to process audio locally, without external conversion services or developer-operated analytics. See the [privacy policy](PRIVACY.md) for details about audio handling and synchronized preferences.

## Project status

**Version 1.0.7 (testing).** Changes to ChatGPT's interface, manual audio downloads, and MP3 conversion still require end-to-end testing before they can be considered stable.

- [Privacy policy](PRIVACY.md)
- [Report an issue](https://github.com/jasp402/ExtractAudioGPT/issues)

*ExtractAudioGPT is an independent project and is not affiliated with OpenAI.*
