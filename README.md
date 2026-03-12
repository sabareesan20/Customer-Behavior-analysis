📌 Overview

This project analyzes customer shopping behavior to identify purchasing patterns, product performance, and customer segments. The goal is to convert raw transactional data into actionable business insights using an end-to-end data analytics workflow.

The project covers the full analytics pipeline including:

📥 Data Loading using Python

🔍 Exploratory Data Analysis (EDA)

🧹 Data Cleaning & Feature Engineering

🗄️ SQL Analysis using PostgreSQL

📊 Dashboard creation in Power BI

📝 Report documentation

📽️ Business presentation created using Gamma

This project demonstrates real-world data analyst skills from raw data to business insights.

📂 Dataset

The dataset contains customer shopping records including demographics, purchase details, and customer behavior.

Key Attributes

👤 Customer Demographics

Age

Gender

Location

🛍️ Product Information

Item Purchased

Category

Size

Color

💰 Purchase Details

Purchase Amount

Season

🎯 Shopping Behavior

Discount Applied

Promo Code Used

Review Rating

🔄 Customer Activity

Previous Purchases

Purchase Frequency

Subscription Status

Shipping Type

🧰 Tools & Technologies
Tool	Purpose
🐍 Python	Data loading, cleaning and EDA
📊 Pandas / NumPy	Data manipulation
📉 Matplotlib / Seaborn	Data visualization
🗄️ PostgreSQL	SQL queries for business analysis
📊 Power BI	Interactive dashboard
📓 Jupyter Notebook	Analysis workflow
📽️ Gamma	Presentation creation
⚙️ Project Workflow
1️⃣ Data Loading

The dataset was imported into Python using Pandas within a Jupyter Notebook environment.

2️⃣ Exploratory Data Analysis (EDA)

EDA was conducted to understand:

Dataset structure

Missing values

Distribution of customer attributes

Purchase patterns

Visualizations were created using Matplotlib and Seaborn.

3️⃣ Data Cleaning

The dataset was cleaned by:

Handling missing values

Standardizing column names

Removing unnecessary columns

Creating additional features for analysis

4️⃣ SQL Analysis (PostgreSQL)

After cleaning, the dataset was loaded into a PostgreSQL database to perform SQL-based business analysis.

Example analyses:

Revenue by gender

Customer segmentation

Top performing products

Discount usage patterns

Subscription vs non-subscription spending

5️⃣ Power BI Dashboard

An interactive dashboard was developed to visualize key business insights.

📊 Dashboard Preview

(Add your Power BI screenshot here)

![Dashboard](images/dashboard.png)
Dashboard Highlights

📈 Revenue trends

👥 Customer segmentation

🛍️ Product category performance

🎯 Discount usage insights

🚚 Shipping type analysis

📊 Results & Insights

Key insights discovered from the analysis include:

Identification of high-value customer segments

Understanding top performing product categories

Insights into customer purchasing patterns

Analysis of discount impact on revenue

Comparison between subscription and non-subscription customers

These insights help businesses improve:

Marketing strategies

Customer retention

Sales performance

📁 Project Structure
Customer-Shopping-Behavior-Analysis
│
├── data
│   └── dataset.csv
│
├── python
│   └── analysis.ipynb
│
├── sql
│   └── queries.sql
│
├── dashboard
│   └── powerbi_dashboard.pbix
│
├── report
│   └── project_report.pdf
│
├── presentation
│   └── gamma_presentation.ppt
│
└── README.md
▶️ How to Run the Project
1️⃣ Clone the repository
git clone https://github.com/yourusername/customer-shopping-behavior-analysis.git
2️⃣ Install required Python libraries
pip install pandas numpy matplotlib seaborn psycopg2
3️⃣ Run the Python Notebook

Open the Jupyter Notebook and run the cells to perform:

Data loading

Data cleaning

Exploratory Data Analysis

4️⃣ Run SQL Queries

Import the cleaned dataset into PostgreSQL

Run the provided SQL script

5️⃣ Open Power BI Dashboard

Open the .pbix file using Power BI Desktop to explore the interactive dashboard.

⭐ Project Outcome

This project demonstrates the ability to:

✔ Work with real-world datasets
✔ Perform data cleaning and EDA
✔ Write SQL queries for business insights
✔ Build interactive dashboards
✔ Communicate insights through reports and presentations
