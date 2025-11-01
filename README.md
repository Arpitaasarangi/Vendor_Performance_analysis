# Vendor_Performance_analysis
📌Overview-
This project analyzes vendor and brand performance in the retail and wholesale sector to improve profitability through smarter inventory, pricing, and purchasing strategies. It identifies top-performing vendors, underperforming brands, and opportunities for bulk purchasing and inventory optimization.

📂 **Dataset**
The analysis is based on six structured CSV files containing multi-dimensional data:
- vendor_invoice.csv
- sales.csv
- purchases.csv
- purchase_price.csv
- begin_inventory.csv
- end_inventory.csv
Each file captures key metrics like ponumber,purchase dates, vendor details, product descriptions, pricing, and inventory levels.

Tools & Technologies
- Python: Data ingestion, cleaning, and analysis
- Pandas & NumPy: Data manipulation and statistical calculations
- Matplotlib & Seaborn: Visualizations (distribution plots, count plots)
- SQLite + SQLAlchemy: Database storage and querying
- Power BI: Interactive dashboard for business insights

🔄 Project Workflow
**Data Ingestion**
Automated loading of CSVs into SQLite using Python and SQLAlchemy with logging for traceability.
**Data Cleaning**
- Removed whitespace and missing values
- Converted volume to float64
- Created new metrics: GrossProfit, ProfitMargin, StockTurnover, SalesPurchaseRatio
**Exploratory Data Analysis (EDA)**
- Record counts and summary statistics
- Distribution plots to detect outliers
- Count plots for top vendors and product descriptions
**Performance Analysis**
- Identified top vendors by sales and gross profit
- Flagged brands with low sales but high margins
- Assessed inventory turnover and purchase contribution
  
📊 **Dashboard Highlights (Power BI)**
- Total Sales: $441.41M
- Total Purchase: $307.34M
- Gross Profit: $134.07M
- Profit Margin: $199.14M
- Top Vendors: Diageo, Martignetti, Pernod Ricard
- Top Brands: Jack Daniels, Tito’s, Grey Goose
- Visuals: Bar charts, contribution %, unsold capital, low-performing vendors/brands

 ▶️**How to Run**
- Clone the repo and place CSV files in a /data folder.
- Run the Python ingestion script to load data into SQLite.
- Execute the analysis notebook (.ipynb) for cleaning, EDA, and metrics.
- Open the Power BI dashboard (.pbix) to explore interactive visuals.


