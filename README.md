# Fable

A mobile-friendly book listening website. Take or upload a photo of a book page, rotate or crop it, review and edit the recognized text, then listen with a voice provided by the browser.

## Publish with GitHub Pages

This is a static website: the entry point is `index.html`, and no build step is needed.

1. Create a GitHub repository and add these project files to its root.
2. In the repository, open **Settings → Pages**.
3. Under **Build and deployment**, choose **GitHub Actions**.
4. Push to the `main` branch. The included Pages workflow publishes the site and shows its address under **Settings → Pages**.

The camera requires HTTPS, which GitHub Pages provides. Photo text recognition downloads Tesseract.js from jsDelivr the first time it is used, so OCR needs an internet connection. Speech playback uses voices installed in the visitor's browser or device. Saved books are kept in that browser's local storage.

## Run locally

Open `index.html` in a modern browser. Photo recognition and camera access work best when served from a local web server or the HTTPS GitHub Pages address.
