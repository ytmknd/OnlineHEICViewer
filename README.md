# Online HEIC Image Viewer

A client-side web application for viewing and converting HEIC images to JPEG, directly in your browser. No sign-up required, no plugins, no server uploads — all processing happens locally on your device.

## Live Demo

**[Try it on GitHub Pages →](https://ytmknd.github.io/OnlineHEICViewer/)**

## Features

- **Drag & drop** one or multiple HEIC files simultaneously
- **Responsive gallery** — view all converted images in a grid layout
- **Lightbox viewer** — click any image for full-screen view; navigate with arrow keys or buttons
- **Quality selector** — choose High (default), Medium, or Low JPEG output quality
- **Individual download** — save each image as JPEG
- **Bulk ZIP download** — download all converted images as a single ZIP archive
- **Internationalization** — displays in Japanese or English based on browser language settings
- **Privacy-first** — files never leave your device

## Usage

1. Open `index.html` in a modern browser (Chrome, Edge, Firefox, Safari)
2. Drag and drop HEIC files onto the upload area, or click **Select Files**
3. Choose output quality: **High / Medium / Low**
4. Converted images appear in the gallery as each file finishes
5. Click a thumbnail to open the full-screen lightbox (← → keys or buttons to navigate, Esc to close)
6. Download individual images with the **Download as JPEG** button, or click **Download ZIP** to get all images at once
7. Click **Clear All** to reset the gallery

## Requirements

A modern browser with WebAssembly support. No installation or build step needed.

| Browser | Support |
|---------|---------|
| Chrome / Edge (latest) | ✅ |
| Firefox (latest) | ✅ |
| Safari (latest) | ✅ |

## Dependencies (loaded from CDN)

| Library | Version | Purpose |
|---------|---------|---------|
| [libheif-js](https://github.com/catdad-experiments/libheif-js) | 1.19.8 | HEIC decoding via WebAssembly |
| [JSZip](https://stuk.github.io/jszip/) | 3.10.1 | ZIP archive creation |

All CDN resources use [Subresource Integrity](https://developer.mozilla.org/en-US/docs/Web/Security/Subresource_Integrity) (SRI) hashes to prevent tampering.

## License

MIT License

Copyright (c) 2024

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
