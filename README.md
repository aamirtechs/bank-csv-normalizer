# Bank CSV Normalizer
Live page: https://aamirtechs.github.io/bank-csv-normalizer/

Convert any bank statement CSV into one clean, categorised format with your own payee rules, without uploading financial data anywhere. It solves the hand-work of doing this job row by row in a spreadsheet, entirely in the browser.

## Features
- Column mapping for any bank export with generic and manual presets
- Sign and debit/credit normalisation into one signed amount
- Date parsing with an explicit DD/MM vs MM/DD setting
- Payee cleanup rules (contains or regex to category) saved locally
- Duplicate row detection and clean CSV export for accounting imports

## How it works
Provide the input in the tool card, run it, review the preview, then download the result. All processing happens locally in your browser using the logic in src/logic.js. No server is involved at any step.

## Privacy
Runs 100% in your browser. Your files never leave this device, nothing is uploaded,
and there is no tracking.

## Development
Core logic lives in `src/logic.js` and is shared by the page and the tests.
Run the tests with `npm test`.

## License
MIT, Copyright 2026 Amir Hussain.
