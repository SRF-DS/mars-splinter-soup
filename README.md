# Mars News + Weather Scrape

## Problem
Mars mission pages and weather tables are scattered across the web — analysts need a reproducible scrape into tidy tables (and optional app/DB wiring).

## What we built
Two notebooks:
- `part_1_mars_news.ipynb` — news scrape → `mars_news.json`
- `part_2_mars_weather.ipynb` — weather scrape → monthly pressure/temp CSVs

## How to run
```bash
pip install splinter beautifulsoup4 selenium pandas jupyter lxml
jupyter notebook part_1_mars_news.ipynb
jupyter notebook part_2_mars_weather.ipynb
```
Site markup changes over time — expect to tweak selectors if a scrape breaks.

## Stack
Python · Splinter / Selenium · BeautifulSoup · pandas · Jupyter

## Fun closer
Scraping Mars weather from Earth is peak "data analyst with a sense of humor."
