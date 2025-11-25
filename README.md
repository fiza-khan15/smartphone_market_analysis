# 📱 Smartphone Market Analysis: Price, 5G & Value Optimization

![Python](https://img.shields.io/badge/Python-3.8%2B-blue)
![Pandas](https://img.shields.io/badge/Library-Pandas-150458)
![Matplotlib](https://img.shields.io/badge/Visualization-Matplotlib-orange)

## 📌 Project Overview
This project analyzes the current smartphone market to identify pricing trends, the "5G premium," and the best value-for-money devices. The goal is to provide data-driven buying recommendations by segmenting the market into Budget, Mid-Range, and Premium categories.

Using a dataset of mobile phones, the project moves through a complete Data Science pipeline: from **collection** to **cleaning** and finally **exploratory data analysis (EDA)**.

---

## 📂 Project Structure
The project is divided into three modular notebooks:

| File Name | Description |
| :--- | :--- |
| **`1_data_collection.ipynb`** | Scripts used to gather raw smartphone data (web scraping/API). |
| **`2_data_cleaning.ipynb`** | Handling missing values, converting data types (Prices, Ratings), and feature engineering (e.g., extracting 5G capability). |
| **`3_data_analysis.ipynb`** | The core analysis. Contains statistical summaries, Matplotlib visualizations, and the "Value Score" algorithm. |
| `cleaned_featured_data.csv` | The final processed dataset ready for analysis. |

---

## 🔍 Key Insights & Findings

### 1. The 5G Premium
* **Insight:** 5G phones are, on average, more expensive than non-5G phones, but the gap is closing as the technology becomes standard.
* **Data:** 5G devices command a price premium of approx. **₹2,400** over 4G counterparts.

### 2. Market Segmentation
* **Budget (< ₹15k):** Dominated by brands focusing on high utility and aggressive pricing.
* **Premium (> ₹30k):** Pricing increases exponentially, often driven by brand value rather than linear hardware improvements.

### 3. Value-For-Money Analysis
I created a custom **Value Score** metric:
$$\text{Value Score} = \left( \frac{\text{Rating}}{\text{Price}} \right) \times 10,000$$

**Top Recommendations based on Data:**
* 💸 **Best Budget Phone:** Ai+ Pulse
* 📱 **Best Mid-Range Phone:** vivo T4x
* 👑 **Best Premium Phone:** Nothing Phone

---

## 📊 Visualizations
*Note: The project uses **Matplotlib** for all visualizations to ensure lightweight and customizable plotting.*

### Price Distribution by Brand
*(You can upload your Boxplot image here, e.g., `![Boxplot](images/boxplot.png)`)*
> *The analysis shows that premium brands have a much wider price variance compared to budget brands.*

### 5G vs Non-5G Pricing
*(You can upload your Bar Chart here)*
> *Visual comparison of average pricing between network generations.*

---

## 🛠️ Tech Stack
* **Python:** Core programming language.
* **Pandas:** Data manipulation and aggregation (Grouping by Brand, Storage).
* **Matplotlib:** Static data visualization (Boxplots, Bar charts).
* **NumPy:** Mathematical operations.

---

## 🚀 How to Run
1. Clone the repository:
   ```bash
   git clone [https://github.com/yourusername/smartphone-analysis.git](https://github.com/yourusername/smartphone-analysis.git)

## Install dependencies:
pip install pandas matplotlib numpy

## Run the notebooks in order:

Start with data_collection (if you need fresh data).
Run data_cleaning to generate the CSV.
Run data_analysis to see the insights.
