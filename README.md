Nashville Neighborhood Redevelopment & Zoning Capacity Analysis
Identify which Nashville neighborhoods are experiencing the strongest redevelopment pressure by analyzing zoning capacity, building activity, and sale price trends.
This replaces demolition permits with a zoning‑based redevelopment potential score, which is a defensible and analytically stronger proxy.

Zoning (Base Zoning Districts)
Source: Nashville Open Data (your current tab)
Provides allowed uses, density, and development intensity
Used to calculate redevelopment potential and zoning capacity

2. Parcels
Source: Nashville Open Data
Provides parcel geometry and zoning attributes
Used to aggregate zoning intensity at the neighborhood level

3. Building Permits
Source: Nashville Open Data
Measures active construction and redevelopment activity

4. Residential Sale Price Trends
Source: Nashville Open Data or scraped MLS summary
Measures value change over time

Key Metrics for the MVP
1. Zoning Redevelopment Potential Score (ZRPS)
A composite score based on zoning intensity:
Low‑intensity (R6, RS10)
Medium (RM9, RM15)
High (RM20+, MUN, MUL)
Very high (SP, DTC, ORI)

2. Building Activity Index
Count of permits per neighborhood
Weighted by permit type (new construction > renovation)

3. Sale Price Change Index
Median sale price change over 5 years
Normalized by neighborhood

4. Neighborhood Transformation Index (NTI)
A combined score of:
Zoning redevelopment potential
Building activity
Sale price growth
This replaces the original “demolition pressure” metric with a zoning‑based approach.

MVP Deliverables
1. Neighborhood‑level dataset (Gold Layer)
A single table containing:
Neighborhood name
Zoning intensity score
Building activity index
Sale price change
Final NTI score

2. Power BI Dashboard
Map of zoning intensity
Map of NTI (ranked neighborhoods)
Bar chart of top 10 transforming neighborhoods
Trend line of sale price change

3. Executive Summary
A short narrative explaining:
Why zoning is used as a redevelopment proxy
Which neighborhoods are transforming fastest
What zoning patterns explain the change
