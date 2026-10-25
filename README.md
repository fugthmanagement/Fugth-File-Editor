# FUGTH File Editor

Private browser-based PDF editing. Open a PDF, locate text from the extracted page list, highlight it, cover it, replace it, and download a new copy.

## Run it

This is a dependency-free static site. Open `index.html` through any static web server, or enable GitHub Pages for the repository.

## Important behavior

- Documents stay in the browser; there is no upload server.
- **Cover** adds an opaque visual redaction. For legal-grade permanent redaction, use a dedicated redaction workflow that removes source text from the PDF structure.
- Text extraction depends on the PDF having a text layer. Scanned image PDFs need OCR before their words appear in the sidebar.

