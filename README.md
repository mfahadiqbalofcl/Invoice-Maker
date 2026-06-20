# Invoice Maker

A clean, client-ready invoice generator built with vanilla HTML, CSS, and JavaScript. Add line items, edit any field inline, and watch totals, balance due, and the amount due recalculate automatically. Everything runs in the browser — no backend, no dependencies, no data leaves the page.

**Live demo:** https://mfahadiqbalofcl.github.io/Invoice-Maker/

## Features

- Fully editable invoice — sender, recipient, dates, and notes are all `contenteditable`
- Add or remove line items on the fly (`+` / `-` controls)
- Automatic calculation of line totals, subtotal, amount paid, and balance due
- Adjust numeric values with arrow keys or the scroll wheel
- Custom currency prefix (defaults to `$`) applied across the invoice
- Drag-and-drop or click-to-upload your own logo
- Print / export to PDF straight from the browser (Ctrl/Cmd + P)
- 100% client-side — works offline, nothing is sent to a server

## Tech Stack

- HTML5 (semantic, `contenteditable` fields)
- CSS3 (minified stylesheet)
- Vanilla JavaScript (no frameworks or libraries)

## Getting Started

No build step or install is required.

1. Clone the repository:
   ```bash
   git clone https://github.com/mfahadiqbalofcl/Invoice-Maker.git
   ```
2. Open `index.html` in any modern browser.

Or simply visit the [live demo](https://mfahadiqbalofcl.github.io/Invoice-Maker/).

> Tip: to serve it locally over HTTP (useful for some browser features), run `python3 -m http.server` from the project folder and open `http://localhost:8000`.

## Usage

1. Click any field to edit it — your details, the recipient, invoice number, and date.
2. Use `+` to add line items and `-` to remove them. Rates and quantities multiply automatically.
3. Click the logo box to upload (or drag and drop) your own logo.
4. Enter the amount paid to see the balance due update.
5. Print or save as PDF with your browser's print dialog (Ctrl/Cmd + P).

## Screenshot

<!-- Add a screenshot of the invoice here -->
![Invoice Maker screenshot](./assets/images/screenshot.png)

## License

Released under the [MIT License](./LICENSE).

---

Built by [M Fahad Iqbal](https://github.com/mfahadiqbalofcl) — Web Designer & Developer.