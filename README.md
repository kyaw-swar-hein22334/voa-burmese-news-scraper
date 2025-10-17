VOA Burmese News Scraper

This is a Python program that collects Burmese news articles from the VOA website. It gets the article titles and text and saves them into JSON files.

What it does

Opens the VOA Burmese news page

Clicks the “Load More” button automatically

Collects all article links

Visits each article and gets the title and text

Saves everything into JSON files in a folder called data

What you need

Python installed on your computer

Libraries: requests, beautifulsoup4, selenium, webdriver-manager

How to use

1. Install the libraries:

pip install requests beautifulsoup4 selenium webdriver-manager


2. Run the scraper:

python voa_scraper.py


3. After it finishes, the data folder will have JSON files with the articles.

Author

Lunar Kim
Beginner Python Developer | Web Scraping Learner
