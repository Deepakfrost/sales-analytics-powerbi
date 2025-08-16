# 📊 Sales Analytics Dashboard

## 📌 Project Overview
The Sales Analytics Dashboard project provides insights into sales performance by analyzing historical sales data and building an interactive dashboard. The goal is to help businesses identify trends, monitor KPIs, and make data-driven decisions.
This project consists of:
A Jupyter Notebook (Sales data analysis.ipynb) for data cleaning, preprocessing, and exploration.
A Power BI Dashboard (Sales Analytics Dashboard.pbix) for interactive visualization and insights.

### 📂 Project Structure

├── Sales data analysis.ipynb      # Data cleaning, EDA, and preprocessing in Python  
├── Sales Analytics Dashboard.pbix # Power BI dashboard for visualization  
├── data/                          # Raw/processed datasets (not included in repo)  
└── README.md                      # Project documentation  

### 📊 Dataset
The dataset contains sales-related information such as:

Order Date – Date of the transaction

Region – Location of the sales

Product Category – Category of items sold

Sales – Sales amount

Quantity – Units sold

### ⚙️ Methodology
1. Data Cleaning & Preprocessing (Python - Jupyter Notebook)
Removed missing/duplicate values
Converted date columns into proper datetime format
Created new calculated fields (e.g., Year, Month, Profit Margin %)
Performed Exploratory Data Analysis (EDA)

2. Dashboard Development (Power BI)
Built an interactive dashboard with:

📈 Sales trends over time

🌍 Regional sales distribution

🛍️ Product-wise performance

💰 Profit vs. Discount analysis

Created KPIs to track revenue, profit, and growth rate

### 🛠️ Tech Stack
Python (Pandas, NumPy, Matplotlib, Seaborn)

Jupyter Notebook

Power BI

GitHub for version control

### ▶️ How to Run

1. Clone this repository
git clone https://github.com/your-username/sales-analytics-dashboard.git

cd sales-analytics-dashboard

2. Install required libraries
   
pip install -r requirements.txt

3. Open the notebook
   
jupyter notebook "Sales data analysis.ipynb"

### 📈 Results & Insights
Identified top-performing regions and product categories

Found correlation between discounts and profit margins

Provided actionable KPIs for decision-making

Created an interactive dashboard for real-time business insights
