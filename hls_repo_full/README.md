# HLS Auto Converter

This repo uses **GitHub Actions** to automatically convert any uploaded `.mp4` or `.mkv` video into HLS (`.m3u8 + .ts`) format using **FFmpeg**.

## How it works
1. Upload or push an `.mp4` or `.mkv` file into the repo root.
2. GitHub Actions workflow runs FFmpeg to convert it into HLS.
3. Output files are deployed to **GitHub Pages**.
4. Access them via:

```
https://<your-username>.github.io/<your-repo>/index.html
```

The included player (`index.html`) automatically lists and plays all generated videos.

A small **sample.mp4** is included for testing.
