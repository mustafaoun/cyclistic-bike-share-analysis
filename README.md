Cyclistic Bike-Share Analysis: Q1 2019 vs Q1 2020
Overview
This project analyzes Cyclistic bike-share data for Q1 2019 and Q1 2020 to understand rider behavior and trends. The goal is to compare key metrics (ride length, number of rides, and peak days) between members and casual riders, identify insights, and provide recommendations to improve membership conversion.
Objectives

Clean and preprocess Cyclistic Q1 2019 and Q1 2020 datasets.
Analyze ride patterns by rider type (member vs casual).
Visualize findings in a PowerPoint presentation.
Provide actionable recommendations for Cyclistic.

Data Sources

Q1 2019 & Q1 2020 datasets from Cyclistic (provided by the Google Data Analytics Capstone).
Stored in data/raw/.
Processed data available in data/processed/cleaned_data.csv.

Project Structure
cyclistic-bike-share-analysis/
├── data/
│   ├── raw/                # Raw datasets (Q1_2019.csv, Q1_2020.csv)
│   ├── processed/          # Cleaned data (cleaned_data.csv)
│   └── README.md           # Data source details
├── scripts/
│   ├── data_cleaning.py    # Data cleaning script
│   ├── analysis.py         # Analysis script (Pivot Tables, metrics)
│   └── conclusions.xlsx    # Summary of conclusions
├── results/
│   ├── Cyclistic_Analysis_2019_vs_2020.pptx  # PowerPoint presentation
│   ├── figures/            # Plot
│   └── summary_tables.xlsx # Summary tables 
├── docs/
│   ├── methodology.md      # Analysis methodology
│   └── insights.md         # Key insights
├── README.md               # This file
├── requirements.txt        # Python dependencies
└── .gitignore              # Ignored files

Methodology

Data Cleaning: Removed missing values, standardized formats, and merged Q1 2019 & Q1 2020 datasets.
Tools: Microsoft Excel for cleaning and Pivot Tables; Python (optional) for scripting.
Analysis:
Calculated average/max ride length, ride counts, and peak days.
Compared member vs casual riders using Pivot Tables.



Key Findings

Casual riders increased usage by 108% in 2020, with longer rides (+34:04 minutes).
Member rides grew by 10.7%, but ride length decreased (-1:13 minutes).
Peak days shifted: Casual (Saturday → Sunday), Members (Thursday → Tuesday).
Overall bike usage grew by 16.9% in 2020.
Details in  results/Cyclistic_Analysis_2019_vs_2020.pptx.

Recommendations

Offer weekend promotions (e.g., Sunday discounts) for casual riders.
Incentivize short rides on peak commuting days (e.g., Tuesday).
Investigate outliers in max ride length (2020).
Promote bike-sharing as eco-friendly to leverage 16.9% growth.

Presentation
The PowerPoint presentation (results/Cyclistic_Analysis_2019_vs_2020.pptx) includes:

Methodology overview.
Key metrics table (2019 vs 2020).
Visualized insights and recommendations.
Open in Microsoft PowerPoint or compatible software.

Acknowledgments

Cyclistic data provided by Google Data Analytics Capstone.
Tools: Microsoft Excel.
