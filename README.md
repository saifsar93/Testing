# Agentic AI Reel Localizer

This project uses Python to build an agentic AI that:

1. Downloads videos from YouTube
2. Transcribes and translates them to Arabic
3. Adds Arabic subtitles in a specified position
4. Adds a logo overlay
5. Outputs a ready-to-post video

## Setup

```bash
pip install -r requirements.txt
```

Make sure you have `ffmpeg` installed and available in your system PATH.

## Run

Edit the `scripts/main.py` file to add your YouTube link and logo path, then run:

```bash
python scripts/main.py
```
