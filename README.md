<div align="center">

# QR Code Maker

A simple, no-frills browser app that turns any text or URL into a downloadable QR code — no install, no backend, just open and go.

[![Use Online](https://img.shields.io/badge/▶_Use_it_Online-2ea44f?style=for-the-badge)](https://ef-krbg.github.io/qrcodemaker/)
[![Download](https://img.shields.io/badge/⬇_Download-0969da?style=for-the-badge)](https://github.com/ef-krbg/qrcodemaker/archive/refs/heads/main.zip)

</div>

---

## About

QR Code Maker is a single-page web app for generating QR codes on the fly. Type in any text or URL, pick a size, and it renders a scannable QR code directly in the browser. Everything runs locally in your browser — no data is sent anywhere.

## Screenshots

<p align="center">
  <img src="docs/screenshots/main.png" alt="QR Code Maker main screen" width="500">
</p>

## Features

- **Instant generation** — QR codes render live in the browser as canvas elements.
- **Custom size** — choose an output size between 100px and 500px.
- **Any text or URL** — links, plain text, Wi-Fi strings, contact info, anything a QR code can hold.
- **Fully self-contained** — plain HTML/CSS/JS with a bundled QR engine, no build step, no external dependencies to install.

---

## Getting Started

Click **Use it Online** above to open the app straight in your browser — nothing to install.

Click **Download** to get a `.zip` of the app. Unzip it and open `index.html` in your browser to run it offline.


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
