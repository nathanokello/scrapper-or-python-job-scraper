# Python Job Listing Scraper

This project scrapes job listings from the Fake Python Jobs website and saves the extracted results as a CSV file.

## Project goals

- Fetch the job listings page
- Extract job title, company, location, and detail URL
- Store the cleaned results in CSV format
- Keep the code simple and readable for learning

## Tech stack

- Python 3
- requests
- BeautifulSoup4
- csv

## Project structure

```text
scrapper/
├── README.md
├── requirements.txt
├── .gitignore
├── src/
│   ├── __init__.py
│   ├── scraper.py
│   └── main.py
├── data/
│   └── jobs.csv
└── projectrequirements.md
```

## Setup

```bash
python -m venv .venv
source .venv/bin/activate   # On Windows: .venv\Scripts\activate
pip install -r requirements.txt
```

## Run the scraper

```bash
python src/main.py
```

The script will fetch the jobs page and write records to `data/jobs.csv`.
