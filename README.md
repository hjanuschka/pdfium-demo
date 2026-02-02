# pdfium-demo

Demo repository for **JXL-in-PDF** bringup in **PDFium** using the **Rust** decoder `jxl-rs`.

The rendered demo page lives in `docs/` and is intended to be served via GitHub Pages.

## What’s inside

- `docs/index.html`: small one-pager showcasing sample PDFs and their rendered PNGs
- `docs/assets/`: PDFs + rendered PNG outputs

## Notes

- Uses an experimental (leader) PDF filter name: `/JXLDecode`
- Animated JXL is rendered as **frame 0 only**
- Alpha is supported by synthesizing a PDF `/SMask`
