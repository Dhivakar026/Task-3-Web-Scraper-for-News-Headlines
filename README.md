# 📰 BBC News Headlines Scraper

This Python script fetches the latest headlines from the [BBC News](https://www.bbc.com/news) website and saves them into a text file (`headlines.txt`). It uses `requests` and `BeautifulSoup` to scrape the content.


---

## 🔧 Requirements

Make sure you have Python installed. Install the required libraries using:

```bash
pip install requests beautifulsoup4
```

---

## 🚀 How to Run

1. Clone or download this repository.
2. Open your terminal or command prompt.
3. Navigate to the folder where `news_scraper.py` is located.
4. Run the script using:

```bash
python news_scraper.py
```

5. After execution, check the `headlines.txt` file for the list of headlines.

---

## 📄 Example Output (`headlines.txt`)

```
1. NewsNews
2. Titan sub firm used 'intimidation tactics'...
3. Dozens feared trapped as cloudburst...
...
```

*Note: Output may vary depending on the current top headlines on the BBC website.*

---

## 📌 Notes

- This script uses `User-Agent` headers to avoid being blocked by the site.
- Headline tags (`h1`, `h2`, `h3`) are commonly used for news titles; you can modify these based on the website structure.
- This is a simple beginner-friendly project to demonstrate web scraping basics.

---




## 👨‍💻 Author

Dhivakar M
