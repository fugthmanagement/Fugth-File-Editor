# FUGTH File Editor

Private browser-based file editing. Open a PDF, image, Word document, or text-based file, then find content, clean it up, and export a copy.

## Run it

This is a dependency-free static site. Open `index.html` through any static web server, or enable GitHub Pages for the repository.

## Important behavior

- Documents stay in the browser; there is no upload server.
- Supports PDF, JPG, PNG, WebP, GIF, DOCX, TXT, Markdown, CSV, and JSON.
- PDF and text documents provide searchable extracted text. Images use a direct drag-to-edit canvas.
- **Cover** and **Clean** are visual layers in the downloaded output. For legal-grade permanent redaction, use a dedicated workflow that removes original PDF source text.
- Text extraction depends on a PDF having a text layer. Scanned image PDFs need OCR before their words appear in the sidebar.

