# WebTools

## [Photomyne Downloader](https://TheHippo999.github.io/WebTools/Photomyne-Downloader.html)
Paste in the URL of a Photomyne lightbox and then download every picture
in the album behind that lightbox.

## [Round Robin](https://TheHippo999.github.io/WebTools/RoundRobin.html)
Generate round robin draws for pickleball doubles events, or any other
sport that plays doubles on designated courts.

## Bedside Clock – Verse Builder

**[Open the Verse Builder](https://thehippo999.github.io/WebTools/bedside-clock/verse-builder.html)**

Builds the encrypted verse file used by the ESP32 Bedside Clock. Load the plain-text `verses.txt` (Berean Standard Bible verses with short reflections), check the line-length and word-count report with on-screen previews, then encrypt and download `verses.json` for upload to the `bedside-clock` folder. The clocks fetch that file over Wi-Fi to update their verses.

- Runs entirely in the browser: nothing is uploaded, and the key is never stored
- AES-256-GCM encryption; the key is entered each time and kept outside the repo
- Reads the live file's version number and bumps it automatically
- Includes tools to recover `verses.txt` from an encrypted file and to generate a first-time key
