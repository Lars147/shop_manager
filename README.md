# Shop Manager

**Shop Manager** is a tool to synchronize Product data and Inventory. Unlike usual ERP business it is focused to receive data not primarily by human but from automated sources.

The goal is to use *web scraping*, *API endpoints* or just *files* to receive data. This data can be manipulated, altered and recalculated. The result will be send to shop systems via API, files or other output.

## Scraping

Shop Manager provides the functionality to scrape data from websites. In order to deploy your own scrapers and run them, Shop Manger uses [**Scrapyd**](https://github.com/scrapy/scrapyd).