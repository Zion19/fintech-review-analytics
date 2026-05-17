## Scraping Methodology

Data was collected using Python with the google-play-scraper libraries.
The scraper visited each product page, extracted titles, prices, and ratings,
and stored the results in CSV format.

Steps:
1. Send HTTP requests to target pages
2. Parse HTML content
3. Extract relevant fields
4. Clean and save structured data

## Date Range

The dataset includes listings scraped between:
- Start date: 2026-05-01
- End date: 2026-05-10

## Limitations

- Some pages blocked automated requests
- A few listings had missing values
- Dynamic JavaScript-loaded content was not captured
- Website structure changes may break the scraper