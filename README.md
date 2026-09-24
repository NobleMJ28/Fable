# Fable

A mobile-friendly book listening website. Take or upload a photo of a book page, rotate or crop it, review and edit the recognized text, then listen with a voice provided by the browser.

## Publish with GitHub Pages

This is a static website. Its entry point is `index.html`, and no build step is needed.

1. Open **Settings → Pages** in this repository.
2. Under **Build and deployment**, select **Deploy from a branch**.
3. Set the branch to **main** and the folder to **/(root)**, then click **Save**.
4. Wait for the published address to appear on the Pages settings screen.

The camera requires HTTPS, which GitHub Pages provides. Photo text recognition downloads Tesseract.js from jsDelivr the first time it is used, so OCR needs an internet connection. Speech playback uses voices available in the visitor’s browser or device. Saved books are kept in that browser’s local storage.

## Run locally

Open `index.html` in a modern browser. Photo recognition and camera access work best when served from a local web server or the HTTPS GitHub Pages address.
