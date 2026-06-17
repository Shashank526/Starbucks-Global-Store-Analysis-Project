# Starbucks-Global-Store-Analysis-Project
This project analyzes Starbucks' global store network using data analytics, SQL, Python, and  Power BI. The objective was to gain insights into store distribution, ownership models, and  geographic expansion opportunities. The dataset consists of approximately 25,600 Starbucks  stores spread across 74 countries and nearly 5,000 cities.

Presentation Link : https://gamma.app/docs/Starbucks-Global-Store-Analysis-5prxs926476z9u4?mode=doc

## Project Overview

This project analyzes Starbucks' global store presence using data analytics and business intelligence techniques. The objective is to uncover insights about store distribution, ownership models, geographic expansion, and market concentration across countries and cities worldwide.

The project demonstrates an end-to-end Data Analytics workflow involving:

- Data Cleaning & Transformation
- Exploratory Data Analysis (EDA)
- SQL Business Queries
- Interactive Power BI Dashboard Development
- Business Insights & Recommendations

---


##  Business Problem

Starbucks operates thousands of stores across multiple countries and regions. Understanding store distribution, ownership structure, and geographical presence can help stakeholders identify:

- High-performing markets
- Expansion opportunities
- Ownership trends
- Regional concentration
- Market penetration levels

---

##  Dataset Information

### Source

Kaggle Starbucks Dataset

### Files Used

#### 1. directory.csv

Contains Starbucks store information:

- Store Number
- Store Name
- Ownership Type
- Street Address
- City
- State/Province
- Country
- Latitude
- Longitude
- Timezone

#### 2. starbucks_drinkMenu_expanded.csv

Contains Starbucks beverage nutritional information.

#### 3. starbucks-menu-nutrition-drinks.csv

Contains drink nutrition details.

#### 4. starbucks-menu-nutrition-food.csv

Contains food nutrition details.

---

##  Technologies Used

### Python

- Pandas
- NumPy
- Matplotlib
- Seaborn

### SQL

- PostgreSQL / MySQL

Concepts Used:

- Aggregations
- Group By
- CTEs
- Window Functions
- Ranking Functions
- Subqueries

### Power BI

- DAX Measures
- KPI Cards
- Maps
- Drillthrough Analysis
- Interactive Slicers
- Decomposition Tree

---

##  Project Workflow

### Phase 1: Data Collection

- Download dataset from Kaggle
- Understand dataset structure
- Identify relevant business questions

### Phase 2: Data Cleaning

Performed:

- Missing value treatment
- Duplicate removal
- Data type correction
- Column standardization
- Data validation

### Phase 3: Exploratory Data Analysis

Analyzed:

- Store distribution by country
- Store distribution by city
- Ownership type distribution
- Geographic concentration
- Regional comparison

### Phase 4: SQL Analysis

Created business queries to answer:

- Top countries by store count
- Top cities by store count
- Ownership model analysis
- Ranking of countries
- Percentage contribution analysis
- Country-wise market concentration

### Phase 5: Power BI Dashboard

Created an interactive dashboard consisting of:

#### Executive Dashboard

- Total Stores
- Total Countries
- Total Cities
- Ownership Types
- Average Stores per Country

#### Geographic Dashboard

- Global Store Map
- Country Ranking
- City Analysis
- Drill-through Insights

#### Business Insights Dashboard

- Expansion Opportunities
- Ownership Comparison
- Market Penetration Analysis

---

##  Key KPIs

| KPI | Description |
|------|------------|
| Total Stores | Total Starbucks stores worldwide |
| Total Countries | Countries with Starbucks presence |
| Total Cities | Cities with Starbucks stores |
| Ownership Types | Number of ownership categories |
| Avg Stores per Country | Average stores per country |
| Avg Stores per City | Average stores per city |

---

##  Power BI Visualizations

### Executive Overview

- KPI Cards
- Filled Map
- Top 10 Countries
- Top 15 Cities
- Ownership Distribution
- Tree Map

### Geographic Intelligence

- Bubble Map
- Heat Map
- Country Ranking
- Decomposition Tree

### Business Insights

- Bottom 10 Countries
- Ownership Analysis
- Market Opportunity Matrix

---

##  SQL Concepts Demonstrated

### Aggregations

```sql
COUNT()
SUM()
AVG()
