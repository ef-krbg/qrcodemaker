<div align="center">

# QR Code Maker

A simple, no-frills browser app that turns any text or URL into a downloadable QR code — no install, no backend, just open and go.

</div>

---

## About

QR Code Maker is a single-page web app for generating QR codes on the fly. Type in any text or URL, pick a size, and it renders a scannable QR code directly in the browser. Everything runs locally in your browser — no data is sent anywhere.

## Screenshots

<p align="center">
  <img src="screenshots/main.png" alt="QR Code Maker main screen" width="500">
</p>

> Add your own screenshot: open `index.html`, generate a code, then save it into `docs/screenshots/main.png`.

## Features

- **Instant generation** — QR codes render live in the browser as canvas elements.
- **Custom size** — choose an output size between 100px and 500px.
- **Any text or URL** — links, plain text, Wi-Fi strings, contact info, anything a QR code can hold.
- **Fully self-contained** — plain HTML/CSS/JS with a bundled QR engine, no build step, no external dependencies to install.

---

## Getting Started

### Use it online

[Open the App](https://ef-krbg.github.io/qrcodemaker/) *(live once GitHub Pages is enabled — see below)*

### Run it locally

No installation needed — it's a static site.

```bash
git clone https://github.com/ef-krbg/qrcodemaker.git
cd qrcodemaker
```

Then just open `index.html` in your browser (double-click it, or right-click → Open With → your browser).

### Enable the live demo (GitHub Pages)

1. Make sure these files are uploaded to the repository.
2. Go to **Settings → Pages**.
3. Under "Build and deployment", set **Source** to `Deploy from a branch`, branch `main`, folder `/ (root)`.
4. The app will be live at `https://ef-krbg.github.io/qrcodemaker/`.

## Project Structure

```
qrcodemaker/
├── index.html      # App markup, styling, and logic
├── js/
│   └── qrcode.js   # Bundled QR code generation engine
├── LICENSE
└── README.md
```

## Tech Stack

HTML · CSS · JavaScript

## License

Distributed under the MIT License. See `LICENSE` for details.

---

<div align="center">

Enes Fatih Karabag — [github.com/ef-krbg](https://github.com/ef-krbg)

</div>
