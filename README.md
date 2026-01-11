# 📌 Project Title
## E-commerce-End-to-End Data Analytics Platform

## 📖 Project Description
This project analyzes historical e-commerce data to provide actionable insights on customer behavior, sales trends, and revenue performance. It identifies patterns in customer churn, regional sales distribution, purchasing habits, and periods of growth or decline. Additionally, predictive analysis forecasts future sales and customer trends to inform strategic business decisions.

The goal is to turn raw data into clear, decision-ready insights that businesses can use to improve service delivery, enhance customer experience, increase retention, and drive sustainable growth.
## Motivation & Problem Statement

Many e-commerce businesses have plenty of data but struggle to use it effectively due to:

Disorganized or incomplete datasets

Lack of reliable analytics pipelines

Difficulty translating insights into actionable strategies

This project was built to bridge that gap by providing a production-style, database-first analytics solution that mirrors real-world business environments.

## Technologies Used

Programming Languages & Libraries:

Python (Pandas, NumPy, Scikit-learn, OpenPyXL, Pycountry)

SQL

Data Processing & Analysis:

ETL pipelines

Data cleaning and transformation

Databases:

SQLite

Visualization & Reporting:

Plotly

Dash

Streamlit

ReportLab

Other Tools:

Excel (for reporting and pivot tables)

## Project Process

The project follows a structured workflow to turn raw e-commerce data into actionable insights:

- Data Collection & Cleaning
   
The project uses messy raw e-commerce datasets generated from multiple sources, including:
[Download raw_data](https://drive.google.com/drive/folders/1cshn-AgXKyteydWAtBkSjXT4FixbDwEU?usp=sharing)

Customers: 50,500 rows × 24 columns

Orders: 101,000 rows × 24 columns

Products: 10,300 rows × 30 columns

Reviews: 50,400 rows × 20 columns



Remove inconsistencies, handle missing data, and standardize formats.

Integrate all datasets into a unified structure.

- Database Creation

Design and populate a relational database (.db file) to efficiently store and manage the data.
[Download .db file](https://drive.google.com/file/d/1BlVZUbcUUVuYTZXYHfy0kBaN8Y83VGN8/view?usp=drive_link)

- Exploratory Data Analysis (EDA)

Analyze and visualize trends in sales, revenue, profit, and customer behavior.

Identify anomalies, seasonal patterns, and key performance drivers.

-  Insight Generation

Detect patterns in customer churn, purchasing habits, and regional distributions.

Produce actionable insights to guide strategic business decisions.

- Predictive Analysis

Forecast future sales and customer trends using historical data.

Support planning, marketing, and inventory management decisions.

- Reporting & Visualization

Build interactive dashboards using Dash and Streamlit.

Generate automated reports for business stakeholders, enabling clear, decision-ready insights.

## 💡 How to Use the Project


- Download the .db file from the provided link.

- Launch the Web Application

- Open the web application locally or on your server.

- Upload the Database

- Navigate to the “Upload Database” section.

- Upload the downloaded Ecommerce.db file.

**_Disclaimer_** - There is no need to place the database in the project directory. The web application handles all database interactions via the upload interface.

- Explore Dashboards and Reports

- The dashboards, analytics, models, and reports load automatically.

- Interact with visualizations, business intelligence dashboards, and automated reports to explore insights.

## Project Insights

- Following data preparation, comprehensive analysis and visualizations were performed to answer key business questions:

- Customer Behavior: Retention trends, churn patterns, and high-risk segments

- Regional & Operational Performance: Regional sales, fulfillment efficiency, and payment failures

- Financial Performance: Product profitability, revenue concentration, and long-term financial trends

## Key findings include:

- A “leaky bucket” retention pattern, showing customers leaving over time

- Declining sales and profit trends

- Operational bottlenecks in delivery and payment processes

- Revenue heavily concentrated among a small group of high-value customers

### Predictive Models

To move beyond descriptive analytics, the project includes predictive models:

- Customer Churn Model

- Uses RFM features (recency, frequency, monetary value)

- Identifies high-risk customers early for targeted re-engagement

- Customer Lifetime Value (LTV) Model

- Highlights future revenue contribution from high-value customers

- Supports smarter prioritization and resource allocation

### Reporting & Deployment

- Automated reporting generates stakeholder-ready PDF reports

- A web application allows users to interact with dashboards, models, and insights in real-time


## Acknowledgements

This project would not have been possible without the collaboration and dedication of my teammates. Their contributions and support were key to the success of this work.


## Future Improvements

- Expand the dataset by incorporating additional publicly available e-commerce data (e.g., from major marketplaces) to enable deeper comparative and trend analysis.
- Enhance predictive models using richer behavioral and product-level features.
- Integrate real-time data sources to support live analytics and monitoring.

