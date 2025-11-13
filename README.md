This project analyzes key logistics performance metrics—delivery efficiency, fuel consumption, and operational costs—using Excel for data preparation and Power BI for dashboard development.
The goal is to provide clear, actionable business insights that help improve delivery reliability, fuel usage, and cost optimization.

⏱ Completed as a focused 2-day short-term assignment, delivering quick turnaround with high-quality analytics.

Objectives
Measure On-Time Delivery % across trips
Analyze Fuel Efficiency (km/L) trends
Calculate Cost per km for operational performance
Compare maintenance vs fuel cost distribution
Enable decision-makers to spot inefficiencies and optimize routes

🧠 Key Metrics (DAX)

On-Time Delivery %
DIVIDE([OnTime Deliveries], [Total Deliveries])
Fuel Efficiency (km/L)
DIVIDE(SUM(Trip_Data[Distance_km]), SUM(Trip_Data[Fuel_Consumed_L]))
Cost per km
(Fuel Cost + Maintenance Cost) / Distance
These DAX measures power the KPI cards and trend visuals in the dashboard.

Dashboard Features

Fuel Efficiency Trend by Delivery Date
Cost per km Analysis
On-Time Delivery Performance
Maintenance & Fuel Cost Comparison
Interactive filters for routes, vehicles, and time periods
Clean UI with focused KPI storytelling

Business Insights

Identified routes with higher cost-per-km → optimization needed
Detected variations in fuel efficiency across delivery dates
Measured on-time delivery consistency
Highlighted trucks/routes consuming more fuel or needing maintenance
Provided a data-driven basis for operational improvements

Author

Alamelu
Power BI Developer & Data Analytics Enthusiast
Focused on delivering actionable insights through simple, effective dashboar
