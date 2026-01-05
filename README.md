# Book Sales and Publishing Dashboard

## Project Overview
This project builds an **interactive decision-support dashboard** for professionals in the book publishing industry. It combines **Python-based data analysis and linear regression modeling** with **Power BI visualizations** to help publishers, analysts, and strategists understand what drives book sales and revenue.

Using a cleaned dataset of **1,070 books**, the project turns raw sales and ratings data into actionable insights that support:
- Sales forecasting  
- Pricing strategy optimization  
- Identification of high-value authors and publishers  

The dashboard delivers both **historical insights** (actual sales and revenue) and **forward-looking insights** through predictive models.

---

## Project Goals
- Analyze key factors influencing book sales and publisher revenue  
- Build linear regression models to predict units sold and revenue  
- Create an interactive Power BI dashboard with KPIs, filters, and “what-if” analysis  
- Translate complex data into easy-to-use business insights  

---

## Tools & Technologies
- **Python**: Data cleaning, exploratory data analysis (EDA), and linear regression modeling  
- **Jupyter Notebook**: Contains all analysis, feature engineering, and predictive modeling  
- **Power BI**: Interactive dashboard with KPIs, filters, and visual insights  
- **Dataset Source**: [Book Sales and Ratings dataset (Kaggle)](https://www.kaggle.com/datasets/thedevastator/books-sales-and-ratings/data)

---

## Dataset Description
The dataset contains **1,070 books**, with each row representing a single title. It includes a mix of numerical and categorical variables, with minimal missing data.

### Key Data Categories
- **Book Information**
  - Title, author, genre, language, publication year
- **Quality Indicators**
  - Average reader rating, rating count, author rating
- **Commercial Performance**
  - Units sold, sale price, gross sales, publisher revenue
- **Publisher Information**
  - Publisher name, sales rank, publisher revenue

---

## Project Structure
- dashboard.pbix --> Interactive PowerBi dashboard
- math.ipynb --> Jupyter notebook with all EDA scrpiting and predictive functions
- Books_Data_Initial.csv --> Data obtained from Kaggle
- cleaned_data.csv --> Data after cleaning and adding additional categorical buckets

---

## Key Performance Indicators (KPIs)
The dashboard includes three main KPI cards that dynamically update based on filters such as genre or publisher:

1. **Publisher Revenue**
   - Measures overall financial performance
   - Supports forecasting and revenue target setting
   - Current value (full dataset): **$4.96 million**

2. **Total / Average Units Sold**
   - Reflects market demand and sales volume
   - Helps identify high-performing genres, authors, and publishing strategies
   - Average units sold per title: **8,960**

3. **Author Rating**
   - Captures reader perception and reputation
   - Strongly correlated with sales performance
   - Average rating: **4.04 / 5**

These KPIs are directly tied to the predictive models built in Python.

---

## Predictive Modeling
- **Linear Regression Models** were developed in Python to predict:
  - Units sold
  - Publisher revenue
- Key predictors include:
  - Author rating
  - Publisher reputation
  - Pricing
- Model outputs are integrated into Power BI to enable **forward-looking analysis** and “what-if” scenarios.

---

## Key Insights
- **Fiction dominates the publishing market** in both sales and revenue  
- **Book pricing varies significantly by publisher**, affecting revenue outcomes  
- **Author ratings are one of the strongest drivers of sales performance**  

---

## Dashboard Features
- Interactive filters (genre, publisher, author)
- KPI cards for high-level performance tracking
- Visual comparisons of actual vs. predicted sales and revenue
- Support for strategic decisions such as:
  - Adjusting prices
  - Setting sales targets
  - Identifying high-value authors and publishers

---

## How to Use
1. Open the **Jupyter Notebook** to review data cleaning, EDA, and regression modeling.
2. Open the **Power BI (.pbix) file** to explore the interactive dashboard.
3. Use filters and KPI cards to test scenarios and uncover insights.



