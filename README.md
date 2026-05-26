# 👗 Vintage Couture — End-to-End Sales Data Analytics

A complete data analytics project for **Vintage Couture**, a fashion retail brand specializing in curated vintage clothing. This notebook walks through the full analytics lifecycle  from raw data ingestion and cleaning to exploratory analysis, visualization, and business recommendations.

---

## 📌 Problem Statement

Vintage Couture had accumulated rich sales transaction data but lacked a structured analysis to turn it into actionable insights. This project addresses key business questions:

- What is the total revenue and when does the brand perform best?
- Which customer demographics (age, gender, region) drive the most revenue?
- How do sales channels and payment methods compare?
- Which states and regions are top performers?
- How does revenue trend month over month?

---

## 📁 Dataset

The analysis uses an Excel workbook (`Vintage_Clothing_Sales_Data.xlsx`) with four sheets:

| Sheet | Description |
|---|---|
| `Vintage Clothing Data` | Core sales transactions |
| `Payment` | Payment method details |
| Sheet 3 | Location/regional data |
| Sheet 4 | Customer demographic data |

All four sheets are merged on their respective keys (`Payment ID`, `Location Id`, `Customer Id`) into a single unified dataframe for analysis.

---

## 🔧 Project Structure & Methodology

The project follows a structured end-to-end analytics workflow:

1. **Problem Statement / Objectives**  Define the business questions
2. **Data Collection**  Load multi-sheet Excel data into pandas
3. **Data Investigation**  Inspect shape, types, and distributions
4. **Data Cleaning & Transformation**  Handle missing values, drop duplicates, engineer features (Age Group, Sales, Month Name)
5. **Exploratory Data Analysis (EDA)**  Univariate, bivariate, and multivariate analysis
6. **Data Storytelling** = Annotated visualizations with business narrative
7. **Recommendations** = Actionable strategies based on findings
8. **Executive Summary** = High-level insights for stakeholders
9. **Limitations** = Caveats and scope boundaries
10. **Report / Communication** = Structured outputs for decision-making

---

## 📊 Key Findings

- **Peak Month:** March recorded the highest revenue (~₦1.7M), with a steady decline toward December (~₦1.4M).
- **Top Segment:** Young Adults (≤30) are the strongest revenue drivers, contributing ~₦6M.
- **Gender Split:** Female customers account for ~68% of sales; male customers ~31%.
- **Sales Channel:** Online dominates over in-store and vendor channels, underscoring the importance of digital strategy.

---

## 🛠️ Tech Stack

- **Python 3**
- `pandas` = data loading, merging, transformation
- `numpy` = numerical operations
- `matplotlib` = base plotting
- `seaborn` = statistical visualizations
- `openpyxl` = Excel file reading

---

## 🚀 Getting Started

```bash
# Clone the repository
git clone https://github.com/your-username/vintage-couture-analytics.git
cd vintage-couture-analytics

# Install dependencies
pip install pandas numpy matplotlib seaborn openpyxl

# Launch the notebook
jupyter notebook vintage_clothing.ipynb
```

> **Note:** Update the `file_path` variable in the notebook to point to your local copy of the Excel dataset before running.

---

## 📂 Output

The notebook exports a merged, cleaned dataset to `vintage_clothing_merged.xlsx` for use in dashboards or further reporting tools (e.g., Power BI, Excel).

---

## 🙋 Author

Built as a portfolio project demonstrating end-to-end data analytics skills  from raw data wrangling to business storytelling.
