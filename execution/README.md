# Execution Scripts

Deterministic Python scripts that do the actual work.

## Principles
- **Deterministic** — Same input → same output, every time
- **Well-commented** — Clear docstrings and inline comments
- **Self-contained** — Each script handles its own I/O and error reporting
- **Testable** — Can be run standalone for verification

## Environment
- API keys and secrets are loaded from `../.env` via `python-dotenv`
- Intermediate files go in `../.tmp/`
- Deliverables go to cloud services (Google Sheets, Slides, etc.)

## Naming Convention

Use descriptive, snake_case filenames matching their directive:
```
scrape_single_site.py
generate_report.py
upload_to_sheets.py
```
