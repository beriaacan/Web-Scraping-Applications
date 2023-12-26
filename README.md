# IMDb Scraper and Web Application

This is a Python project that combines the power of Scrapy for web scraping and crawling with Flask for micro web development using the Werkzeug framework. The project is organized into two subprojects:

## 1. IMDb Scraper

The IMDb Scraper is designed to extract information about specific movies from the Internet Movie Database (IMDb). The scraped data is then persistently stored in a MongoDB database. MongoDB was chosen as the ideal database for this use case, allowing each movie to be represented as a document.

### How to Use

1. Navigate to the `imdb_scraper` folder.
2. Run the Scrapy spider to scrape IMDb data.
    ```bash
    scrapy crawl imdb_spider
    ```
3. The scraped data will be stored in the MongoDB database.

## 2. Web Application

The Web Application is responsible for rendering the IMDb data gathered by the scraper. It provides a user-friendly interface for exploring the movie information.

### How to Use

1. Navigate to the `web_application` folder.
2. Run the Flask application.
    ```bash
    flask run
    ```
3. Open your web browser and go to [http://localhost:5000](http://localhost:5000) to access the IMDb data.

## Requirements

- Python
- Scrapy
- Flask
- MongoDB



