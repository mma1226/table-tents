# Modal Table Tents

Upload an `.xlsx` or `.csv` guest list and download a print-ready table tent PDF:
3.75 × 5 in, folds at 2.5 in, top panel mirrored, dark or light style.
Everything runs in the browser. No data leaves your machine.

**Live:** https://mma1226.github.io/table-tents/

## Spreadsheet format

First row is headers. Columns are auto-detected and can be remapped in the page:

- `First name` + `Last name`, or a single `Name` column (first word on line 1, rest on line 2)
- `Company`

Long names scale down to fit and are flagged in the preview.

## Files

- `index.html` — the generator
- `template.pdf`, `template-light.pdf` — vector backgrounds and logos
- `bg.jpg`, `bg-light.jpg` — on-screen preview backgrounds
- `Inter-*.ttf` — fonts embedded in the PDF (SIL Open Font License)
