# About

**Viral Clipper Pro (ClipperAI)** is a Windows desktop app that turns long YouTube or local videos into vertical YouTube Shorts (9:16) and a 16:9 compilation video. AI picks the best moments from the transcript, and the app handles transcription, face-tracked framing, subtitles, transitions, watermarks, and thumbnails.

## Short description (GitHub "About" box)

> Desktop app that uses AI to turn long videos into YouTube Shorts (9:16) and compilation videos (16:9), with auto subtitles, face-tracked framing, and thumbnails.

## Topics (suggested)

`youtube-shorts` `video-editing` `ai` `whisper` `mediapipe` `opencv` `ffmpeg` `customtkinter` `python` `desktop-app` `thumbnail-generator`

## Features

- Import from YouTube links (up to 3 at a time) or local video files
- Automatic transcription with Whisper (fast, balanced, or accurate models)
- Optional English to Indonesian translation
- AI moment selection with Google Gemini, OpenAI, Claude, OpenRouter, or a custom endpoint
- 8–14 clips per video, with a total compilation length of at least 8 minutes
- Face-tracked 9:16 framing with single-subject or split-screen modes
- Kinetic subtitles with three styles
- Compilation video with transitions (random, fade, slide, zoom, circle)
- Auto-generated titles, descriptions, chapters, and hashtags
- Watermarks: two optional text overlays with position choices
- Thumbnail Studio for 9:16 and 16:9 thumbnails, with automatic frame selection

## Requirements

- Windows 10 or 11 (64-bit)
- Python 3.11 (only needed to build from source)
- FFmpeg (`ffmpeg.exe`)
- An API key from at least one supported AI provider

## Installation

Download `ClipperAI-Setup.exe` from the Releases page and run it, or build from source:

```bat
py -3.11 -m venv .venv
.venv\Scripts\activate
pip install -r requirements.txt
python stable_app_claude.py
```

API keys are stored locally on your computer and are only sent to the provider you choose.

## Notes

- Whisper models are downloaded on first use, so an internet connection is needed the first time.
- Respect the copyright and platform terms of any video you download and clip.

## License

MIT License

Copyright (c) [year] [fullname]

Permission is hereby granted, free of charge, to any person obtaining a copy
of this software and associated documentation files (the "Software"), to deal
in the Software without restriction, including without limitation the rights
to use, copy, modify, merge, publish, distribute, sublicense, and/or sell
copies of the Software, and to permit persons to whom the Software is
furnished to do so, subject to the following conditions:

The above copyright notice and this permission notice shall be included in all
copies or substantial portions of the Software.

THE SOFTWARE IS PROVIDED "AS IS", WITHOUT WARRANTY OF ANY KIND, EXPRESS OR
IMPLIED, INCLUDING BUT NOT LIMITED TO THE WARRANTIES OF MERCHANTABILITY,
FITNESS FOR A PARTICULAR PURPOSE AND NONINFRINGEMENT. IN NO EVENT SHALL THE
AUTHORS OR COPYRIGHT HOLDERS BE LIABLE FOR ANY CLAIM, DAMAGES OR OTHER
LIABILITY, WHETHER IN AN ACTION OF CONTRACT, TORT OR OTHERWISE, ARISING FROM,
OUT OF OR IN CONNECTION WITH THE SOFTWARE OR THE USE OR OTHER DEALINGS IN THE
SOFTWARE.
