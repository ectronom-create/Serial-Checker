# Serial Number Checker

A browser-based tool to scan and verify serial numbers across uploaded batch files (.xlsx, .xls, .csv).

## Features

- **Batch File Upload:** Upload multiple files (.xlsx, .xls, .csv). Each file is stored locally as its own batch.
- **Multiple Serial Field Matching:** Checks scans against:
  - Serial Number Palette
  - Box Serial Number
  - Factory Serial Number
  - Serial Number
- **Local Persistence:** Data is stored locally in the browser using IndexedDB.
- **Single & Multi-Scan Checking:** Instant validation for single barcode scans or bulk list verification with status counts.
