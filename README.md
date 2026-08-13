# Swiggy Restaurant & Delivery Performance Analysis

A beginner-friendly business analysis project using **Excel and Microsoft Power BI** to analyze restaurant presence, pricing, customer ratings, food categories, and delivery performance.

## Business Objective

Analyze restaurant and delivery-related data to identify patterns across cities, areas, restaurants, food categories, pricing, customer ratings, and delivery times, and translate the findings into practical business questions and recommendations.

## Key Business Questions

- Which cities and areas have the largest restaurant presence?
- Which locations have relatively higher delivery times?
- How do customer ratings vary across cities and restaurants?
- How does listed price vary by city and food category?
- Which restaurants have high rating volume or lower ratings that may warrant investigation?
- Which areas could be prioritized for operational review?

## Tools Used

- **Microsoft Excel** — data preparation, formulas, PivotTables, KPI analysis
- **Power BI** — data modeling, DAX, interactive dashboarding, KPI visualization and business analysis

## Dataset

The project uses a Swiggy restaurant dataset containing restaurant, location, pricing, rating, and delivery-time fields.

The dataset includes fields such as:

- ID
- Area
- City
- Restaurant
- Price
- Average Rating
- Total Ratings
- Food Type
- Address
- Delivery Time

## Analysis Workflow

**Raw Data → Data Quality Checks → Data Preparation → Excel/PivotTable Analysis → Power BI Dashboard → Business Insights → Recommendations**

## Power BI Dashboard

The dashboard is organized into four analytical pages:

1. **Executive Overview** — headline KPIs and overall performance view
2. **City & Location Analysis** — restaurant presence, pricing, ratings and delivery performance by location
3. **Restaurant & Food Analysis** — restaurant-level and food-category analysis
4. **Delivery & Business Insights** — delivery-time patterns and areas requiring further investigation

## Key Metrics

The project focuses on consistently defined metrics including:

- Restaurant records
- Unique restaurants
- Number of cities and areas
- Average rating
- Average listed price
- Average delivery time
- Total rating volume

> **Metric note:** Average listed price represents the price field available in the dataset. It should not be interpreted as average order value or revenue because the dataset does not contain transaction-level sales data.

## Business Analysis Approach

The analysis focuses on descriptive and diagnostic questions rather than claiming causation. For example, relationships between price, ratings, restaurant presence, and delivery time are treated as patterns that may require further investigation rather than proof that one factor directly causes another.

## Project Files

- `PowerBI/` — Power BI report
- `Excel/` — supporting Excel analysis
- `Screenshots/` — dashboard previews

## Limitations

- The dataset is observational and does not contain order-level revenue, profit, customer-level, or transaction-level information.
- Listed price should not be treated as actual customer spend.
- Relationships observed in the dashboard do not establish causation.
- Some analytical categories are defined for this project and may not represent official Swiggy classifications.

## Author

**Alvin Atelier**

Business Analytics / Business Analyst Portfolio Project
