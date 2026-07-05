# Market Sentiment & Trader Behavior Analysis

## Overview
This project analyzes the impact of market sentiment (Fear vs. Greed) on retail and whale trader behavior. By processing raw trading logs and merging them with daily sentiment indexes, this data science pipeline identifies how psychological market states dictate trade frequency, leverage scaling, long/short bias, and ultimate profitability.

## Technologies Used
* **Python 3.x**
* **Pandas:** Data manipulation, merging, and behavioral metric aggregation.
* **Matplotlib & Seaborn:** Statistical data visualization and exploratory data analysis (EDA).
* **Jupyter Notebook:** Interactive development and presentation.

## Setup & Installation

**1. Clone the repository**
```bash
git clone https://github.com/TanyaShedde/market-sentiment-analysis.git
```
**2. Install dependencies**

Ensure you have the required Python libraries installed:

```bash
pip install pandas matplotlib seaborn jupyter
```

**3.Data Requriments**

Due to GitHub's file size limits, the raw datasets  are excluded from this repository via .gitignore.To run this code locally, you must provide your own historical trading data and sentiment index CSV files.Place the CSV files directly in the root directory of this project before executing the notebook.

**How to Run**

Launch Jupyter Notebook from your terminal in the project directory:

```bash
jupyter notebook
```
