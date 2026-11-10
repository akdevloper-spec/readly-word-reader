# Readly — Free Word Reader PWA

Free, no Azure, no API key, no subscription. Reads using browser/device speech synthesis.

## Setup
1. Deploy files to an HTTPS host such as GitHub Pages.
2. On Android Chrome open the site → menu → Install app / Add to Home screen.
3. In Android settings find Text-to-speech output, install/configure English voice packs.
4. Back in Readly, select accent group and a voice, upload `.docx`, tap Play.

## Limitations
- Voice selection is determined by installed voices on the Android device. Five distinct feminine English accents cannot be guaranteed across devices.
- Browser's speech synthesis may vary in whether voices work offline. Download voice data in Android TTS settings for offline availability.
- DOCX extraction uses Mammoth.js from jsDelivr CDN; first load/parser retrieval requires internet.
- Document text is extracted locally; no cloud TTS endpoint is used.
