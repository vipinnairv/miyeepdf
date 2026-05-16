Vipin's PDF Suite Miyee PDF
A privacy-first PDF toolkit that runs entirely in your browser.

Miyee PDF is a complete PDF productivity suite built for people who care about what happens to their documents. Unlike popular online PDF tools that quietly upload your files to remote servers, Miyee PDF processes everything on your own device your contracts, bank statements, ID documents, and personal records never leave your computer. There are no accounts to create, no emails to surrender, no analytics watching over your shoulder, and no files quietly cached on someone else's cloud.

The suite bundles six powerful tools in a single, lightweight HTML application. Merge combines multiple PDFs in any order you choose. Organize lets you visually reorder, delete, or insert pages with drag-and-drop thumbnails. Word → PDF converts .docx files in seconds, and Image → PDF stitches JPGs and PNGs into clean multi-page documents with adjustable page sizes and orientations. The Annotate tool delivers an Adobe-style editor with text selection, inline text insertion, multi-color highlighting, sticky-note comments, draggable annotations, and a proper redaction tool with color picker  perfect for blacking out sensitive information before sharing. Finally, OCR uses Tesseract.js to extract text from scanned PDFs or images in eight languages, exporting either plain text or a fully searchable PDF.

Everything is built on trusted open-source libraries  pdf-lib, pdf.js, Mammoth.js, jsPDF, and Tesseract.js  and runs in a single HTML file with zero installation, zero server costs, and zero backend. Drop it on any static host and your users get a fully working PDF editor that respects their privacy by design.

Whether you're a finance professional handling sensitive client documents, a legal team reviewing confidential agreements, a healthcare worker managing patient records, or simply someone who values digital sovereignty, Miyee PDF gives you the convenience of online tools without the privacy compromise. Your documents stay on your computer. Always.

Built by Vipin · for users who care about Data Safety.

Vipin's PDF Suite  Miyee PDF · Feature List
🔗 Merge / Combine PDF
Drag-and-drop multiple PDFs at once
Reorder files with ↑ / ↓ controls before merging
Remove individual files from the queue
One-click merge into a single output PDF
🗂️ Organize PDF
Visual thumbnail grid of every page
Drag-and-drop reordering of pages
Delete any page
Insert blank pages anywhere
Append pages from another PDF (merge mid-document)
Save as a new reorganized PDF
📝 Word → PDF
Convert .doc / .docx to PDF in-browser (Mammoth.js)
Live preview before export
Editable output filename
Multi-page support with A4 layout
🖼️ Image → PDF
JPG and PNG → single PDF
Multiple images per document, reorderable
Page size: A4 or Letter
Orientation: Auto (per image), Portrait, or Landscape
Auto-fit with margin, centered on page
✏️ Annotate PDF
Continuous multi-page view with zoom (100% – 200%)
🖱️ Select Text  real text selection via pdf.js layer, Ctrl+C to copy
🅣 Add Text  inline editor on the page, custom color picker, font-size control
🖍️ Highlight  drag-to-draw with 6 preset colors + custom color picker
💬 Comment  sticky-note style with Save / Cancel buttons, multi-line
▮ Redact  solid color block to cover content; white/black/navy/maroon/gray/yellow + custom
All annotations are draggable after placement
Hover-to-show × handle for one-click delete
All edits flattened into a single downloadable PDF
🔎 OCR (Text Recognition)
Works on scanned PDFs and image files (JPG/PNG)
Powered by Tesseract.js  runs entirely on-device
8 languages: English, Hindi, French, German, Spanish, Chinese (Simplified), Arabic, Japanese
Live per-page progress indicator
Side-by-side view: original page image + extracted editable text
Two export options:
Download plain .txt (with page separators)
Download Searchable PDF (original images + invisible text layer for search/select)
🔒 Data Safety Protocol
No uploads  all processing happens in your browser
No tracking  zero analytics, cookies, or telemetry
No persistence  files live only in tab memory; closing the tab wipes them
No accounts  no sign-in, no email collection
OCR runs on-device  Web Worker, models cached locally
Works offline after first load
🎨 Design & UX
Light theme, rose accent branding (Miyee PDF identity)
Responsive layout  sidebar tool nav + main workspace
Sticky toolbar in editor for always-accessible controls
Custom dropzones with drag-and-drop file intake
Inline loading spinners with status text
Branded header with "M" logo and "Built by Vipin · for users who care about Data Safety" footer
🛠️ Technical Stack (Hosting Notes)
Single self-contained HTML file  MiyeePDF.html
No build step  React + Babel via CDN, Tailwind via CDN
No backend  purely client-side, can be hosted on any static host
Recommended hosts: GitHub Pages, Netlify, Vercel, Cloudflare Pages, S3 + CloudFront, or any plain web server
Just upload the single HTML file and point your domain at it
First load requires internet (CDN assets); subsequent loads work offline if browser cached the libraries
No environment variables, no API keys, no database, no server costs
