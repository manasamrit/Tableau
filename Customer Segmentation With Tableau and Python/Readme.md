# 🚗 Data Analytics Customer Segmentation 📊

---

## Goal of the Project
The primary aim of this project is to conduct Customer Segmentation Analysis for an Automobile bike Company. The segmentation is achieved through the development of an RFM (Recency, Frequency, Monetary) Model. RFM analysis is a behavior-based approach that categorizes customers into segments based on their past purchase transactions. The analysis involves dividing the customer segment into 11 groups. The insights gained from this analysis will aid in identifying the customer segments to target, thereby enhancing sales revenue for the company. Additionally, a Sales Dashboard for Customer Segmentation has been developed using Tableau, while Python was employed for data quality assessment and analysis.

---

## Tableau Dashboard
The Sales Dashboard for Customer Segmentation can be accessed [here](#).

In case of difficulties loading Jupyter Notebooks on Github, the following notebooks can be viewed on nbviewer:
- [RFM Analysis.ipynb](#)
- [DQA and Data Cleaning CustomerDemographic.ipynb](#)
- [DQA and Data Cleaning NewCustomerList.ipynb](#)
- [DQA and Data Cleaning Transactions.ipynb](#)
- [DQA and Data Cleaning Customer Address.ipynb](#)

---

## Analysis Approach
### 1. Data Quality Assessment and Data Cleaning
The initial step involves data preparation, quality assessment, and cleaning. This includes:

- Assessing data quality and dropping irrelevant columns.
- Handling missing values by either dropping records or imputing appropriate values.
- Standardizing data to remove inconsistencies.
- Transforming data, such as converting Date of Birth to 'Age' and 'Age Group' columns.
- Checking for and removing duplicate records.

### 2. Exploratory Data Analysis on Customer Segments
Following data cleaning, exploratory analysis is conducted, yielding insights such as:

- Age distribution among new and old customers.
- Gender-based bike purchase trends over the last three years.
- Job industry distribution among customer segments.
- Wealth segmentation by age category.
- Car ownership distribution by states.

### 3. RFM Analysis and Customer Segmentation
Customer segmentation is performed by developing an RFM Model, categorizing customers into 11 segments based on Recency, Frequency, and Monetary metrics. The segments include Platinum Customers, Very Loyal Customers, Recent Customers, and more.

### 4. RFM Analysis: Scatter Plots
Scatter plots are used to visualize relationships between Recency, Frequency, and Monetary metrics. Insights include observations on recent customer purchasing behavior, frequency, and monetary contributions from various customer segments.

---

## Datasets Used
The project utilized the following datasets:

- **Raw_data.xlsx**: Included transactions data, new customer details, customer demographics, and customer addresses.
- **Transactions_data.xlsx**: Transactions data of customers across different Australian states.
- **NewCustomerList.xlsx**: Details of new customers visiting the automobile bike company.
- **CustomerDemographic.xlsx**: Comprehensive customer demographic information.
- **CustomerAddress.xlsx**: Customer address data.

---

## Tools and Technologies Used
The project employed the following tools and technologies:

- **Python**: Used for Data Quality Assessment, Data Cleaning, and exploratory data analysis with libraries like pandas, matplotlib, and seaborn.
- **Tableau**: Utilized as a Business Intelligence tool for data exploration and visualization, resulting in the creation of a Sales Dashboard for Customer Segmentation.

---

## Built With
Python 3.8.2, Tableau
