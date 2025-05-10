# 🛍️ Amazon Product Scraper & Analysis

A complete Python-based solution to **scrape sponsored product data from Amazon India**, clean and prepare the dataset, and extract **insights through analysis and visualizations**.

---

## 🎯 Objective

This project aims to:

1. **Scrape product data** from [Amazon.in](https://www.amazon.in) for a specific keyword (e.g., `"soft toys"`).
2. **Analyze the data** to uncover meaningful and actionable insights.
3. Present the findings using **clean, insightful visualizations**.

---

## 📦 Features

- 🔎 Scrapes **sponsored products** from Amazon search results
- 📊 Extracts key data: `Title`, `Brand`, `Reviews`, `Rating`, `Price`, `Image URL`, `Product URL`
- 🧹 Cleans and formats the scraped data
- 📈 Performs 3 major types of analysis:
  - **Brand Performance**
  - **Price vs. Rating**
  - **Review & Rating Distribution**
- 📉 Generates charts like bar plots, pie charts, and scatter plots
- 📝 Saves output as CSV and plots as images (if desired)

---

## 🛠️ Tech Stack

- `Python 3`
- `Selenium` (for dynamic scraping)
- `BeautifulSoup` (for parsing HTML)
- `Pandas` (for data manipulation)
- `Matplotlib` & `Seaborn` (for visualization)
- `Google Colab` friendly

---

## 🚀 How to Run

1. **Clone the repository**
   ```bash
   git clone https://github.com/yourusername/amazon-product-scraper.git
   cd amazon-product-scraper
   ```

2. **Install dependencies**
   ```bash
   pip install -r requirements.txt
   ```

3. **Run the scraper**
   Open the notebook in Colab or run the Python script:
   ```bash
   python amazon_scraper.py
   ```

4. **Analyze the data**
  
---

## 📊 Sample Insights

- **Top Brands:** Most frequent and highest-rated sponsored brands
- **Value Products:** Low-price, high-rating outliers
- **Popularity Trends:** Products with most reviews vs. those with highest ratings

---

## 📁 Output

- `amazon_sponsored_soft_toys.csv` — Cleaned dataset


---

## ⚠️ Disclaimer

- This project is for **educational and research purposes** only.
- Scraping Amazon may violate their terms of service. Use responsibly and consider their [robots.txt](https://www.amazon.in/robots.txt) and policies.

---

## 📬 Contact

For questions or feedback, reach out to:  

Email: rusheelhere@gmail.com
