
##  Project Overview

This project analyzes global supply chain performance using **Power BI** to provide actionable insights into revenue, manufacturing costs, defect rates, logistics efficiency, and product performance.

The dashboard helps stakeholders monitor operational efficiency, cost management, and identify supply chain bottlenecks across different locations and product categories.

---

## Tools & Technologies Used

- Power BI  
- MS Excel  
- DAX (Data Analysis Expressions)

Project Level: Intermediate

---

##  Dataset Information

The dataset contains detailed supply chain lifecycle data including:

- Product Type (Skincare, Haircare, Cosmetics)
- SKU (Stock Keeping Unit)
- Revenue Generated
- Number of Products Sold
- Manufacturing Costs
- Lead Times
- Shipping Costs
- Shipping Carriers
- Defect Rates
- Location (Mumbai, Delhi, Kolkata, Bangalore, Chennai)

---

##  Key Performance Indicators (KPIs)

### Total Revenue
```DAX
Total Revenue = SUM('supply_chain_data'[Revenue generated])
```

### Total Manufacturing Cost
```DAX
Total Cost = SUM('supply_chain_data'[Manufacturing costs])
```

###  Average Defect Rate
```DAX
Avg Defect Rate = AVERAGE('supply_chain_data'[Defect rates])
```

### Total Products Sold
```DAX
Total Items Sold = SUM('supply_chain_data'[Number of products sold])
```

---

##  Dashboard Visualizations

### Map – Geographic Revenue Distribution
- Location-based revenue analysis
- Bubble size represents Total Revenue
- Identifies high-performing cities

###  Donut Chart – Shipping Cost by Carrier
- Compares shipping costs across Carrier A, B, and C
- Identifies most expensive logistics partner

### Clustered Bar Chart – Cost vs Revenue by Product Type
- Compares Manufacturing Cost and Revenue
- Evaluates product profitability

### Line Chart – Lead Time Analysis by SKU
- Tracks lead time variations
- Identifies supply chain delays and bottlenecks

---

## Interactive Filters (Slicers)

- Location
- Product Type
- Shipping Carrier

These slicers allow dynamic and interactive analysis.

---

## Dashboard Creation Process

### Step 1: Data Preparation
- Imported CSV file into Power BI
- Cleaned and formatted numeric fields
- Verified data types

### Step 2: Created DAX Measures
- Built KPI measures for Revenue, Cost, Defect Rate, and Items Sold

### Step 3: Built Visualizations
- Added Map, Donut Chart, Bar Chart, and Line Chart

### Step 4: Added Slicers
- Implemented interactive dropdown filters

### Step 5: Dashboard Design
- Clean professional theme
- Structured layout
- KPI section at top
- Analytical visuals in middle and bottom sections

---

## Key Insights

- Identified top-performing cities by revenue.
- Compared manufacturing cost vs revenue to evaluate profitability.
- Analyzed shipping cost distribution across carriers.
- Detected high lead-time SKUs indicating operational inefficiencies.
- Monitored defect rate to assess product quality performance.

---

##  Business Impact

This dashboard enables:

- Data-driven decision-making  
- Cost optimization  
- Improved logistics planning  
- Better inventory management  
- Reduction of supply chain bottlenecks  

---



