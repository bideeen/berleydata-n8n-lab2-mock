# BerleyData n8n Lab 2 - mock country service

Practice / mock data for the BerleyData n8n cohort Lab 2. This is not real data, and the repository contains no personal data.

It is a static stand-in for `GET /country/{code}` and returns `{ "region", "currency" }` for four country codes only: NG, GH, KE and ZA. Any other code returns HTTP 404.

Base URL: `https://raw.githubusercontent.com/bideeen/berleydata-n8n-lab2-mock/main/country/`

Example: `https://raw.githubusercontent.com/bideeen/berleydata-n8n-lab2-mock/main/country/NG.json`

Both `/country/NG.json` and `/country/NG` work. Files are served as `text/plain`, so in the n8n HTTP Request node set Response Format to JSON.






