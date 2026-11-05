# WMMT3DX+ // Mobile Archive

A responsive, unofficial fan-made **prank download landing page** supporting Traditional Chinese, English, Japanese, Indonesian, and Filipino.

## Run

Open `index.html` in a modern browser, or serve the folder as a static website. For a local server, run:

```bash
python -m http.server 8000
```

Then browse to `http://localhost:8000`.

**Keep `assets/ad-video.mp4` next to `index.html` in the provided folder structure.** The package contains a web-optimized copy of the video you provided. No external services, paid fonts, or dependencies are required.

## What happens

- Allannn-sudo: Android and iOS tabs, versions 1.22, 1.24, 1.29, and 1.33.
- Nxy: iOS 1.7.2 and Android 1.7.4.
- Clicking any download button opens a fictional sponsored-video screen (same video for every button).
- The page has no skip/close control during the video. Video completion triggers a simulated loading screen and then the prank message, translated into the active language.
- The video is not an actual third-party ad. No game download files are included, and no data is collected.

**Note:** Preventing skipping is a front-end user-interface behavior, not DRM; users can always close the browser or modify their own client-side page. Some browsers require an additional tap to begin media playback.

## Deploy

Upload all contents of the folder to any static hosting provider such as GitHub Pages, Netlify, Cloudflare Pages, or your own web server. Make sure `.mp4` files are served with the `video/mp4` content type. There are no APIs or build steps.
