# Cyclistic Bike-Share Analysis: Q1 2019 vs Q1 2020

## 📌 Overview
This project analyzes Cyclistic bike-share data for Q1 2019 and Q1 2020 to understand rider behavior and trends. The goal is to compare key metrics (ride length, number of rides, and peak days) between **members** and **casual riders**, uncover insights, and provide strategic recommendations to improve membership conversion.

---

## 🎯 Objectives

- Clean and preprocess Cyclistic Q1 2019 and Q1 2020 datasets.
- Analyze ride patterns by rider type (member vs casual).
- Visualize findings in a PowerPoint presentation.
- Provide actionable recommendations for Cyclistic.

---

## 📂 Data Sources

- **Raw Datasets**: Q1 2019 & Q1 2020 data from Cyclistic (via Google Data Analytics Capstone).
- **Raw files location**: `data/raw/`
- **Processed file**: `data/processed/cleaned_data.csv`

---

## 🗂️ Project Structure

cyclistic-bike-share-analysis/
├── data/
│   ├── raw/                # Raw datasets (Q1_2019.csv, Q1_2020.csv)
│   ├── processed/          # Cleaned data (cleaned_data.csv)
│   └── README.md           # Data source details
├── scripts/
│   ├── data_cleaning.py    # Data cleaning script (if used)
│   ├── analysis.py         # Analysis script (if used)
│   └── conclusions.xlsx    # Summary of conclusions
├── results/
│   ├── Cyclistic_Analysis_2019_vs_2020.pptx  # PowerPoint presentation
│   ├── figures/            # Plots or screenshots (if any)
│   └── summary_tables.xlsx # Summary tables (if any)
├── docs/
│   ├── methodology.md      # Analysis methodology
│   └── insights.md         # Key insights
├── README.md               # This file
├── requirements.txt        # Python dependencies (if used)
└── .gitignore              # Ignored files


---

## ⚙️ Methodology

- **Data Cleaning**: Removed missing values, standardized date/time formats, merged Q1 2019 and Q1 2020 data.
- **Tools**:
  - **Microsoft Excel**: Data cleaning, pivot tables
  - **Python** *(optional)*: Automation scripts
- **Analysis Highlights**:
  - Average and max ride lengths
  - Ride counts per rider type
  - Peak days and usage patterns

---

## 📊 Key Findings

- **Casual riders** increased usage by **108%** in 2020, with **longer rides (+34:04 mins)**.
- **Member rides** grew by **10.7%**, but **average ride length decreased (-1:13 mins)**.
- **Peak day shifts**:
  - Casual: *Saturday → Sunday*
  - Members: *Thursday → Tuesday*
- **Overall usage** increased by **16.9%** from 2019 to 2020.

More details available in `results/Cyclistic_Analysis_2019_vs_2020.pptx`.

---

## ✅ Recommendations

- **Weekend promotions** (e.g., Sunday discounts) to engage casual riders.
- **Incentivize short rides** on peak commuting days (e.g., Tuesday).
- **Investigate outliers** in ride lengths (especially 2020 max values).
- **Promote eco-friendly messaging** to capitalize on 16.9% growth.

---

## 📽️ Presentation

The PowerPoint file `results/Cyclistic_Analysis_2019_vs_2020.pptx` includes:

- Methodology overview
- Key comparison tables (2019 vs 2020)
- Visual insights and action-driven recommendations

Open using **Microsoft PowerPoint** or compatible software.

---

## 🙏 Acknowledgments

- **Data Source**: Cyclistic data via *Google Data Analytics Capstone*
- **Tools Used**: Microsoft Excel, Python (optional)

---

