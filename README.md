# Overview

Scraper for Hansard parliamentary proceedings, taken from [here](https://sprs.parl.gov.sg/search/home). Use in conjunction with my `pq_analyzer` repo.

# Usage

Install dependencies using `pip` and `requirements.txt`. I don't think there's any specific python version you need to use. Run the two scraping notebooks first to scrape the data into `.html` files (will be in the `scraped_content/` directory), then run the cleaning notebook to combine the data and clean it up into a nice `.csv` file.

# Remarks

The Hansard proceedings are full of errors and inconsistencies. If the scraper/cleaner give any errors, consider opening the relevant document and seeing if there's any edge case. I tried to account for those I could find but there's no guarantee that I got everything; after all there's really a lot of documents.  
