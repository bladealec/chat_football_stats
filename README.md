# NISA League Web Scraping Project

**Disclaimer**: This project is intended solely for educational and learning purposes. Please use it responsibly.

This repository contains a set of Python scripts that facilitate data scraping and automation tasks related to the National Independent Soccer Association (NISA) website. These scripts gather data from various NISA web pages and automate the process of executing Jupyter notebooks. The repository includes the following scripts:


### Player Statistics Scraper
- [**player_stats_scraper.ipynb**](player_stats_scraper.ipynb):
   - This script gathers data on NISA player statistics tables.
   - It uses web scraping techniques with libraries like `requests`, `BeautifulSoup`, and `Selenium` to extract data from web pages.
   - You can download player statistics tables for different years and seasons.

### Team Standings Scraper
- [**team_standings_scraper.ipynb**](team_standings_scraper.ipynb):
   - This script gathers data on NISA team standings tables.
   - Similar to the player statistics script, it uses web scraping to extract data.
   - It can download team standings for different years and seasons.

### League Statistics Scraper
- [**league_stats_scraper.ipynb**](league_stats_scraper.ipynb):
   - This script gathers data on NISA league statistics tables.
   - It follows the same web scraping approach as the other scripts.
   - You can download league statistics for different years.

### Automation Script
- [**automation_script.ipynb**](automation_script.ipynb):
   - This script automates the process of reading, running, and saving Python notebooks.

## Libraries Used

These scripts make use of several Python libraries for web scraping, data extraction, and automation, including:
- `requests`: Used to send HTTP requests to web pages.
- `BeautifulSoup`: Utilized for parsing HTML and extracting data from web pages.
- `Selenium`: Enables web automation for interaction with web elements.
- `nbconvert`: Used for running and saving Jupyter notebooks programmatically.


## Automated Weekly Task

These scripts are designed for both manual and automated use. You can set up a weekly automated task using a task manager to run the automation script (`automation_script.ipynb`). This way, you can collect data regularly without having to run the scripts separately.
