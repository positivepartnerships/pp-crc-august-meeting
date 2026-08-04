# PP + Autism CRC Meeting — Info Booklet (August 2026)

Info booklet website and PDF for the Positive Partnerships and Autism CRC collaboration gathering, Rydges South Bank Brisbane, 10–12 August 2026.

- `index.html` — the website (GitHub Pages ready)
- `PP-CRC-Meeting-Info-Booklet-August-2026.pdf` — distributable PDF, linked from the site
- `pdf.html` — print-layout source used to generate the PDF

To regenerate the PDF after editing `pdf.html`:

```sh
"/Applications/Google Chrome.app/Contents/MacOS/Google Chrome" --headless --disable-gpu \
  --no-pdf-header-footer \
  --print-to-pdf="PP-CRC-Meeting-Info-Booklet-August-2026.pdf" pdf.html
```
