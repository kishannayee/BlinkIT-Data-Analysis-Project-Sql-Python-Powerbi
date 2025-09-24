
#  🛒 Blinkit Sales Analysis

Analyzing sales performance, customer satisfaction, and inventory efficiency to support data-driven decisions using Python and Power BI.


## 📌 Table of Contents

- <a href="#overview">Overview</a>
- <a href="#business-problem">Business Problem</a>
- <a href="#dataset">Dataset</a>
- <a href="#tools--technologies">Tools & Technologies</a>
- <a href="#project-structure">Project Structure</a>
- <a href="#exploratory-data-analysis-eda">Exploratory Data Analysis (EDA)</a>
- <a href="#research-questions--key-findings">Research Questions & Key Findings</a>
- <a href="#dashboard">Dashboard</a>
- <a href="#how-to-run-this-project">How to Run This Project</a>
- <a href="#final-recommendations">Final Recommendations</a>
- <a href="#author--contact">Author & Contact</a>

---
<h2><a class="anchor" id="overview"></a>Overview</h2>

This project analyzes Blinkit’s sales performance, customer satisfaction, and inventory distribution to generate insights for business optimization. Data was processed using Python for cleaning and EDA, while Power BI was used to build interactive dashboards for KPI monitoring.

---
<h2><a class="anchor" id="business-problem"></a>Business Problem</h2>

Retail businesses like Blinkit face challenges in balancing sales growth, customer satisfaction, and inventory efficiency. Inefficient strategies can lead to stockouts, reduced profitability, or customer dissatisfaction.

This project aims to:

Analyze the impact of fat content, item type, and outlet establishment type on sales.
Identify top-performing and underperforming outlets by size and location.
Assess customer satisfaction using average ratings.
Provide insights into sales distribution trends for better decision-making.
Support inventory and resource allocation with data-driven insights.

<h2><a class="anchor" id="dataset"></a>Dataset</h2>

File Format: CSV

Key Features:

- Item Type

- Item Fat Content

- Item Sales

- Outlet Size

- Outlet Establishment Year

- Outlet Location

- Average Customer Ratings

- Target Variable: Total Sales

<h2><a class="anchor" id="tools--technologies"></a>Tools & Technologies</h2>

- Python (Pandas, NumPy, Matplotlib, Seaborn) → Data Cleaning & EDA

- Power BI → Interactive dashboards & KPI visualization

- Excel/CSV → Dataset storage

- GitHub → Version control & collaboration

- SQL (Common Table Expressions, Joins, Filtering)

<h2><a class="anchor" id="project-structure"></a>Project Structure</h2>
blinkit-sales-analysis/
│
├── data/                        # Raw dataset (CSV)
├── notebooks/                   # Jupyter notebooks for analysis
│   ├── data_analysis.ipynb
│   
│
├── dashboard/                   # Power BI dashboard
│   └── blinkit_sales_dashboard.pbix
│
├── reports/                     # Final reports (PDF/Docs)
│   └── Blinkit_Sales_Report.pdf
│
│
└── README.md


<h2><a class="anchor" id="exploratory-data-analysis-eda"></a>Exploratory Data Analysis (EDA)</h2>

Charts & Insights:

- Total Sales by Fat Content → Donut Chart
- Total Sales by Item Type → Bar Chart
- Fat Content by Outlet for Sales → Stacked Column Chart
- Sales Trend by Outlet Establishment Year → Line Chart
- Sales by Outlet Size → Pie/Donut Chart
- Sales by Location → Funnel Map

<h2><a class="anchor" id="research-questions--key-findings"></a>Research Questions & Key Findings</h2>

**Low-Fat Items**: Contribute a significant portion of sales → customers show preference for healthier options.

**Hypothesis Test**: Sales of low-fat items are statistically higher compared to regular items (p < 0.05).

**Top Item Types**: Fruits & Vegetables, Snack Foods, and Household items generate the majority of revenue.

**Outlet Age Impact**: Older outlets show stable but moderate sales, while newer outlets capture higher average sales.

**Outlet Size Correlation**: Large outlets drive the highest revenue, while small outlets underperform.

**Location Profitability**: Tier-1 city outlets contribute the highest revenue and customer satisfaction.

**Hypothesis Test**: Mean sales in Tier-1 outlets are significantly higher than Tier-2 and Tier-3 (p < 0.01).

KPI Variance by Attributes:

Total Sales: Driven by outlet size & location.
Average Sales: Higher in modern outlets.
Number of Items: Larger outlets offer significantly more variety (p < 0.05).
Average Rating: Statistically higher for fresh categories vs. packaged foods.

<h2><a class="anchor" id="dashboard"></a>Dashboard</h2>

The Power BI dashboard includes:

- KPI Cards: Total Sales, Average Sales, Number of Items, Avg Rating
- Sales distribution by Item Type & Fat Content
- Outlet Size & Location comparison
- Time-series analysis of sales trends

<h2><a class="anchor" id="how-to-run-this-project"></a>How to Run This Project</h2>

Clone the repository:

git clone https://github.com/yourusername/blinkit-sales-analysis.git


Place dataset into /data/ folder.

Run preprocessing script:

- python scripts/preprocessing.py
- Open Jupyter notebooks to run EDA:
- notebooks/data_cleaning.ipynb
- notebooks/exploratory_analysis.ipynb
- Open Power BI file:
- dashboard/blinkit_sales_dashboard.pbix

<h2><a class="anchor" id="final-recommendations"></a>Final Recommendations</h2>

- Promote top-selling item types to maximize revenue.
- Introduce discounts or campaigns for underperforming outlets.
- Improve customer satisfaction by focusing on low-rated items.
- Optimize inventory for high-demand locations.
- Monitor outlet age vs. sales performance to guide future store openings.

<h2><a class="anchor" id="author--contact"></a>Author & Contact</h2>

Kishan Nayee
Data Analyst | BI Enthusiast
📧 Email: nayeekishan4@gmail.com  
🔗 [LinkedIn](https://www.linkedin.com/in/kishan-nayee-14789631a/)

