# Analyzing Tesla and GameStop Stock vs Revenue Data

This project is part of the **IBM Python for Data Science** course on Coursera. The objective is to analyze historical stock prices and revenue data for **Tesla (TSLA)** and **GameStop (GME)** using Python.

---

## Project Overview

The project demonstrates:

1. Extracting stock price data using the `yfinance` library.
2. Web scraping revenue data from Macrotrends using `BeautifulSoup` and `pandas`.
3. Cleaning and preprocessing financial data.
4. Visualizing historical stock prices using **Plotly**.
5. Comparing stock performance with revenue trends.

---

## Project Structure

| File                           | Description                                                                                 |
| ------------------------------ | ------------------------------------------------------------------------------------------- |
| `Stock_Revenue_Analysis.ipynb` | Main Jupyter Notebook containing all code for data extraction, cleaning, and visualization. |
| `README.md`                    | Project documentation.                                                                      |

---

## Libraries Used

* `yfinance` – Download historical stock data.
* `pandas` – Data manipulation and cleaning.
* `requests` – Fetch HTML pages for web scraping.
* `BeautifulSoup` – Parse HTML and extract tables.
* `plotly` – Interactive stock price visualizations.

---

## How to Run

1. Clone the repository:

```bash
git clone <your-repo-link>
```

2. Navigate to the project folder:

```bash
cd <project-folder>
```

3. Install required libraries:

```bash
pip install yfinance pandas requests beautifulsoup4 plotly
```

4. Open the Jupyter Notebook:

```bash
jupyter notebook Stock_Revenue_Analysis.ipynb
```

5. Run each cell sequentially to reproduce the results.

---

## Analysis Steps

1. **Tesla Stock Data** – Extracted using `yfinance` and displayed first 5 rows.
2. **Tesla Revenue Data** – Scraped from Macrotrends, cleaned, and last 5 rows displayed.
3. **GameStop Stock Data** – Extracted using `yfinance` and displayed first 5 rows.
4. **GameStop Revenue Data** – Scraped from Macrotrends, cleaned, and last 5 rows displayed.
5. **Visualization** – Line plots for Tesla and GameStop stock prices over time.

---

## References

* [yfinance Documentation](https://pypi.org/project/yfinance/)
* [BeautifulSoup Documentation](https://www.crummy.com/software/BeautifulSoup/bs4/doc/)
* [Macrotrends](https://www.macrotrends.net/)
* IBM Python for Data Science Course, Coursera

---

## Honor Code

I, **Aditya Nanaware**, certify that this submission is my own work for the Coursera IBM Python for Data Science course.
