# 📈 Ethereum Hourly Price Analysis (Data Analyst Project)

This project performs an in-depth analysis of Ethereum (ETH) prices using hourly data. Using **Pandas** and **Matplotlib**, we clean the data, extract trends, and visualize insights to better understand Ethereum's behavior over time.

---

## 🧰 Tools & Technologies

- Python
- Pandas
- Matplotlib
- Jupyter Notebook

---

## 📦 Dataset

- **Source**: Public Ethereum price data (hourly intervals)
- **Format**: CSV
- **Columns**:  
  - `Date` (datetime)  
  - `Open`, `High`, `Low`, `Close`  
  - `Volume`  
  - `Symbol`

---

## 🔧 Project Workflow

### 1. Data Cleaning
- Parsed `Date` column as datetime and set as index
- Sorted by time
- Removed missing or malformed rows

### 2. Yearly Trend Analysis
- Resampled data using yearly intervals
- Calculated average yearly `Close` price
- Visualized using a clean line chart

### 3. Rolling Average (30-Day)
- Computed a rolling average over 30 days (720 hours)
- Visualized with raw hourly close price + trendline

---

## 📊 Visualizations

### 📅 Yearly Average Close Price

Shows Ethereum’s average price per year, revealing long-term trends and cycles.

### 🔁 30-Day Rolling Average

Smoothed view of hourly fluctuations to identify volatility, bull runs, or corrections.

---

## 💡 Key Insights

- Clear yearly growth trends in specific periods (e.g. 2017, 2020).
- Rolling averages highlight both stable and volatile phases.
- Hourly granularity provides a detailed look at short-term market behavior.

---

## 🚀 How to Run This Project

```bash
# Clone the repo
git clone https://github.com/your-username/ethereum-price-analysis.git

# Open Jupyter Notebook
cd ethereum-price-analysis
jupyter notebook
