# 👨🏻‍💻Customer Shopping Behavior Analysis

## 📌 Project Overview
This project analyzes customer shopping behavior using transactional retail data.  
The objective is to uncover insights into **customer demographics, purchasing patterns, product preferences, and subscription behavior** to support data-driven business decisions.

The project follows a complete **data analytics workflow** including data loading, exploratory data analysis (EDA), data cleaning, SQL-based business analysis, dashboard creation, and reporting.

![Project Workflow](https://github.com/user-attachments/assets/8bbd5dc9-eb6c-40c1-8f19-c08b4107f654)

---

## 🛠️Dataset
The dataset contains retail transaction records with customer and purchase information.

**Dataset Summary**
- Total Records: 3,900 transactions
- Total Features: 18 columns

**Key Features**
- Customer Demographics: Age, Gender, Location, Subscription Status
- Purchase Details: Item Purchased, Category, Purchase Amount, Season, Size, Color
- Shopping Behavior: Discount Applied, Previous Purchases, Frequency of Purchases
- Customer Feedback: Review Rating
- Delivery Information: Shipping Type

The dataset was cleaned and prepared before performing further analysis.

---

## 📊Tools & Technologies
- **Python** – Data loading, cleaning, and exploratory data analysis  
- **Pandas & NumPy** – Data manipulation and preprocessing  
- **SQL (PostgreSQL / MySQL / SQL Server)** – Business queries and analysis  
- **Power BI** – Data visualization and dashboard creation  
- **Gamma** – Presentation creation  
- **GitHub** – Project version control and portfolio showcase  

---

## 🚀Project Workflow

### 1. Data Loading
- Imported dataset into Python using **Pandas**
- Performed initial exploration using:
  - `df.info()`
  - `df.describe()`
  - `df.head()`

### 2. Exploratory Data Analysis (EDA)
- Analyzed data distribution
- Checked data types and missing values
- Explored relationships between variables
- Identified patterns in customer purchasing behavior

### 3. Data Cleaning & Preparation
- Handled missing values in the **Review Rating** column
- Standardized column names using **snake_case**
- Removed redundant columns
- Created additional features such as:
  - Age Groups
  - Purchase Frequency

### 4. Database Integration
- Connected Python to SQL database
- Loaded cleaned dataset into **PostgreSQL / MySQL / SQL Server**

### 5. SQL Data Analysis
Performed SQL queries to answer key business questions:

- Revenue comparison by gender
- High spending customers using discounts
- Top rated products
- Shipping type comparison
- Subscribers vs non-subscribers spending
- Discount dependent products
- Customer segmentation (New / Returning / Loyal)
- Top 3 products in each category
- Repeat buyers and subscription behavior
- Revenue contribution by age group

### 6. Power BI Dashboard
An interactive dashboard was built to visualize key insights including:

- Total revenue
- Customer segments
- Category-wise sales
- Age group analysis
- Product performance
- Subscription behavior

The dashboard helps stakeholders quickly understand trends and patterns in customer purchasing behavior.

### 7. Reporting & Presentation
- A detailed **analysis report** was created summarizing findings.
- A **PowerPoint presentation** was generated using Gamma to present insights clearly.

---

## 📚Key Insights & Results
- Certain product categories contribute the highest revenue.
- Loyal customers generate a significant portion of total sales.
- Subscription users tend to have higher spending patterns.
- Discounts influence purchasing behavior but require balance to maintain profit margins.
- Certain age groups contribute more significantly to total revenue.

These insights can help businesses improve **marketing strategies, product positioning, and customer retention programs.**

---

## 📜How to Run This Project

### 1. Clone the Repository
```bash
git clone https://github.com/sakshi-chauhan0207/customer-shopping-behavior-analysis.git
```

### 2. Install Required Libraries
```bash
pip install pandas numpy sqlalchemy psycopg2
```

### 3. Run the Python Script
Load the dataset and perform EDA and data cleaning.

### 4. Import Data into SQL
Use PostgreSQL / MySQL / SQL Server to run analysis queries.

### 5. Open Power BI Dashboard
Load the dataset or database connection to view the dashboard.

---

## 💼Project Structure
```
customer-shopping-behavior-analysis
│
├── data
│   └── dataset.csv
│
├── python
│   └── data_cleaning_eda.ipynb
│
├── sql
│   └── analysis_queries.sql
│
├── dashboard
│   └── powerbi_dashboard.pbix
│
├── report
│   └── project_report.pdf
│
└── README.md
```

---

## 👨‍💻 Author
**Sakshi Chauhan**

BCA Student | Aspiring Data Analyst  
Interested in **Data Analytics, SQL, Visualization, and Business Insights**
