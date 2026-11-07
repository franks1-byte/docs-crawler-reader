# Fine Print Crawler

A web app that reads your documents for you. Upload a `.docx`, `.pdf`, `.txt` or `.md` file and a spider-like crawler moves across the text word by word:

- **Purple** highlights mark the document's keywords.
- **Orange** tags flag risky lines, like `¶ Forever`, `¶ Without Notice`, `¶ Shared With Others` and `¶ Trains AI On You`.
- **Yellow** tags mark deadlines, requirements and important notes.

When the scan finishes, it creates a **.docx summary** automatically. The summary has an overview, key points, highlighted sentences, grouped flags, keywords and a section-by-section summary.

## Run it

Open `index.html` in a browser, or turn on GitHub Pages for this repo (Settings → Pages → Deploy from branch → `main`).

Everything runs in the browser. Your files are never uploaded anywhere.

## Built with

- [mammoth.js](https://github.com/mwilliamson/mammoth.js) to read Word files
- [PDF.js](https://mozilla.github.io/pdf.js/) to read PDFs
- [docx](https://docx.js.org/) to write the summary file

Made by John Francis.
