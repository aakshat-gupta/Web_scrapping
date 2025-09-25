Web Scraping Books Data

This project demonstrates **web scraping with Python** using the [Books to Scrape](https://books.toscrape.com/) website.  
The scraper extracts **book titles, prices, and ratings**, and saves the results into a structured dataset for analysis.

---

🔹 Features
- Downloads all **50 pages** of the book store and saves them locally in an `htmls/` folder.  
- Supports downloading a **single page** for testing.  
- Parses the saved HTML files with **BeautifulSoup**.  
- Extracts:
  - 📖 **Title**  
  - 💲 **Price** (cleaned from encoding issues like `Ã‚Â£`)  
  - ⭐ **Rating**  
- Stores data into a **Pandas DataFrame** and exports it as `scrapping_data.csv`.

---

🔹 Technologies Used
- [Python 3](https://www.python.org/)  
- [requests](https://docs.python-requests.org/) – for fetching pages  
- [BeautifulSoup (bs4)](https://www.crummy.com/software/BeautifulSoup/) – for parsing HTML  
- [pandas](https://pandas.pydata.org/) – for storing/exporting data  

---

🔹 How to Run
1. Clone this repository:
   ```bash
   git clone https://github.com/yourusername/books-scraper.git
   cd books-scraper
