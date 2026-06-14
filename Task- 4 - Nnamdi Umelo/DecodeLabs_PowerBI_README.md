# Decode Labs E-Commerce Sales Dashboard (Power BI)

## Project Overview
This project is an interactive Power BI dashboard built to analyze e-commerce sales performance, customer purchasing behavior, marketing effectiveness, and operational efficiency.

## Business Objectives
- Measure total revenue and orders
- Analyze product performance
- Evaluate marketing channels
- Track delivery and cancellation rates
- Understand customer payment preferences

## Tools Used
- Power BI Desktop
- Power Query
- DAX
- Data Modeling

## Step-by-Step Development Process

### Step 1: Data Import
1. Open Power BI Desktop
2. Click Get Data
3. Import the dataset
4. Load data into Power BI

### Step 2: Data Cleaning
- Remove duplicates
- Handle missing values
- Correct data types
- Standardize column names

### Step 3: Data Transformation
- Create date hierarchy
- Create Month fields
- Validate measures

### Step 4: DAX Measures
#### Total Revenue
```DAX
Total Revenue = SUM('Decodelabs_Project1'[TotalPrice])
```

#### Total Orders
```DAX
Total Orders = COUNTROWS('Decodelabs_Project1')
```

#### Average Order Value
```DAX
Average Order Value = DIVIDE([Total Revenue], [Total Orders])
```

### Step 5: Dashboard Design
- KPI Cards
- Revenue Trend Analysis
- Product Performance Analysis
- Marketing Analysis
- Customer Insights

## Dashboard Components

### Sales Overview Page
- Total Revenue
- Total Orders
- Average Order Value
- Cancellation Rate
- Revenue by Product
- Monthly Revenue Trend

### Marketing & Customer Insights Page
- Delivery Rate
- Coupon Usage Rate
- Referral Source Analysis
- Payment Method Analysis

## Key Insights

### Sales Insights
- Revenue trends reveal seasonal performance.
- Top products contribute the largest share of revenue.
- Average order value helps monitor customer spending.

### Operational Insights
- Delivery rate measures fulfillment efficiency.
- Cancellation rate identifies operational issues.

### Marketing Insights
- Referral sources reveal high-performing acquisition channels.
- Coupon analysis measures promotion effectiveness.

### Customer Insights
- Payment method analysis highlights customer preferences.
- Customer purchasing patterns support business planning.

## Business Value
This dashboard helps stakeholders:
- Make data-driven decisions
- Improve operational efficiency
- Optimize marketing investments
- Monitor business performance in real time

## Author
Nnamdi Umelo
