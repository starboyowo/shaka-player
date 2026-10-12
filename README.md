# stream. — Clean Web Player

A responsive Shaka Player frontend for authorized MPEG-DASH (`.mpd`) and HLS (`.m3u8`) streams.

## Deploy on Vercel
1. Upload `index.html` to a GitHub repository.
2. In Vercel, choose **Add New → Project** and import that repository.
3. Use the default settings and deploy. No build command is needed.

## Run locally
Open `index.html` in a modern browser, or serve this folder using any static web server.

## Notes
- The stream host must allow CORS for browser playback.
- Temporary signed URLs can expire.
- DRM-protected streams need the authorized license and configuration from the stream provider. This page does not bypass DRM or generate access tokens.
- Some codecs (for example HEVC) may not be supported by every browser/device.
