# Tanush Gupta: portfolio

A static site. No build step, no dependencies.

- `index.html` holds all five pages (four chapters and the final page).
- `img/` holds the stylized photos and project screenshots.
- `resume-tanush-gupta.pdf` is the file the Resume buttons open.
- `og.png` is the link-preview image (needs the live address, see below).

## Edit
Open `index.html`, change the text, save. Each chapter is one `<article class="page">`.

## Publish
Any static host works. Upload this folder as it is.

## After you have the live address
In `index.html`, add these two lines inside `<head>` (use your real address):

    <meta property="og:url" content="https://YOUR-ADDRESS/">
    <meta property="og:image" content="https://YOUR-ADDRESS/og.png">
