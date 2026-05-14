# Doctern — Features

A detailed look at what Doctern does. (Marketing documentation — no implementation details.)

## Optical Character Recognition (OCR)

Doctern reads text from documents that aren't already machine-readable:

- Scanned paper documents
- Photos of documents taken on a phone
- Image-only PDFs
- Low-resolution, skewed, or noisy scans

The result is clean, selectable text — even when the original was just pixels.

## Structured Table Extraction

Most tools flatten tables into a jumble of words. Doctern doesn't.

- **Cell-level detection** — identifies the boundaries of each cell.
- **Row/column integrity** — keeps data in the right place so a value never lands in the wrong column.
- **Header recognition** — distinguishes header rows from data rows.
- **Borderless tables** — reconstructs tables that have no drawn grid lines by analyzing layout.

Output is spreadsheet-ready — paste straight into Excel or Google Sheets.

## Intelligent Field Matching

Documents of the same type rarely share the exact same layout. Doctern finds the **values you care about** regardless of where they sit on the page:

- Invoice numbers, dates, totals, tax amounts
- Names, addresses, reference codes
- Any custom field you define

## Modern Web Experience

- Drag-and-drop upload
- Live preview of extracted content
- One-click export
- Clean, fast interface

## Built for Reliability

- Production-grade Python / FastAPI backend
- Deep-learning OCR and computer-vision table detection
- Structured, predictable output formats
