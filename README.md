📖 Project Overview
This project performs end-to-end exploratory data analysis (EDA) on the Superstore dataset, uncovering key business insights such as:

📦 Best and worst performing product categories
🌍 Regional sales and profit distribution
👥 Customer segment behavior
📅 Time-series trends in orders and revenue
💸 Impact of discounts on profitability

Dataset Summary
PropertyDetailRows9,994 ordersColumns21 featuresDate RangeJanuary 2017 – September 2017CategoriesFurniture, Office Supplies, TechnologySegmentsConsumer, Corporate, Home OfficeRegionsEast, West, Central, South

✨ Features

✅ Data Quality Check — null values, blanks, and data type validation
📊 Sales Analysis — revenue breakdown by category, sub-category, and region
📈 Profit Analysis — identifying high-margin and loss-making products
🗺️ Geographic Analysis — state and city-level performance maps
👤 Customer Segmentation — behavior by Consumer, Corporate, and Home Office segments
🔍 Discount Impact — correlation between discounts and profit margins


🗂️ Project Structure
superstore-analysis/
│
├── data/
│   └── Superstore.csv          # Raw dataset
│
├── notebooks/
│   └── eda.ipynb               # Exploratory Data Analysis notebook
│
├── src/
│   ├── data_cleaning.py        # Data preprocessing scripts
│   ├── analysis.py             # Core analysis functions
│   └── visualizations.py      # Chart and plot generation
│
├── outputs/
│   └── figures/                # Exported charts and plots
│
├── requirements.txt
└── README.md
