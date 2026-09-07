# Salute Inspector

Salute Inspector is a lightweight, browser-based Error Level Analysis (ELA) tool built for community moderators. It detects digital manipulation and text overlays on user-uploaded salute signs by highlighting JPEG re-compression inconsistencies in real time. It operates 100% client-side with zero data uploads, keeping verification fast and private.

## Features
* **Real-Time ELA Analysis:** Instantly highlights compression inconsistencies around digitally edited or overlaid text.
* **Image URL Loading:** Paste, drag/drop, or clipboard-load direct `http/https` image URLs without downloading locally first.
* **100% Client-Side:** Processes images entirely in the browser using HTML5 Canvas—no photos are uploaded to any server.
* **Adjustable Compression Scale:** Features an interactive slider to fine-tune JPEG quality levels for subtle edit detection.
* **Zero Configuration:** Works out of the box in any modern browser on desktop or mobile.

## How to Use
1. Open the live web app: https://anomoly247.github.io/salute-inspector/
2. Load an image using either:
   - **Select Image File** for local uploads, or
   - Paste a direct `http/https` link into **Image URL** and click **Load Image** (you can also use **Paste URL** or drag/drop a URL).
3. Review the **ELA Compression Heat Map** side-by-side with the original photo.
4. Look for bright, high-contrast outlines around text or graphics, which indicate digital manipulation.

## URL Mode Notes
* URL mode fetches images directly in your browser with a timeout and image-type checks.
* Some hosts block cross-origin requests (CORS) or do not expose direct image links; if URL load fails, use another host or local file upload.
