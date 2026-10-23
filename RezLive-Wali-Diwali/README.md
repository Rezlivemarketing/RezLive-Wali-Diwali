# RezLive Wali Diwali

A mobile QR photo booth. It runs person segmentation in the visitor's browser with MediaPipe Selfie Segmentation, so the selected travel background is visible live behind the person before they capture a photo.

## Host it

Upload the contents of dist/ to GitHub Pages, Netlify, Cloudflare Pages, or any static host. It must be served over HTTPS for browser camera access.

For final campaign art, replace the third value of each places entry in dist/index.html with your approved 9:16 portrait city image (recommended: 2160 × 3840 px).

## Privacy and technical note

Camera frames are processed locally in the browser; the project does not upload or store employee photos. The segmentation model downloads on first use and needs a modern Chrome, Safari, or Edge browser plus internet access.
