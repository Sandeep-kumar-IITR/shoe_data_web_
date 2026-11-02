# Shoe Data Web Scraping

A small web-scraping experiment. The repository contains a Jupyter notebook and a CSV file with the collected shoe data.

## Files

- `shoe_data_web_scraping_sandeep_kumar.ipynb` — scraping and data-collection notebook.
- `shoe_data.csv` — resulting dataset.

## Run locally

```bash
python -m venv .venv
# Windows: .venv\\Scripts\\activate
# macOS/Linux: source .venv/bin/activate
pip install pandas requests beautifulsoup4 jupyter
jupyter notebook
```

The notebook may require additional libraries depending on the scraping implementation.

## Responsible scraping

Check the target site's terms, robots policy and applicable law before running scraping code. Keep request rates modest, identify the source of collected data and avoid collecting personal information.

## Author

Sandeep Kumar
