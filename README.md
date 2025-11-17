# Uber-Power-BI-
This Uber Data Analytics Dashboard provides insights into ride trends, demand patterns, revenue, and driver performance. Built using Power BI with Power Query, data modeling, and DAX measures, the project delivers interactive visuals to support decision-making in transportation analytics.


📌 Project Overview

This project presents an interactive Uber Data Analytics Dashboard built using Power BI to analyze key ride metrics such as total trips, revenue, peak hours, popular routes, and driver performance. The goal is to help stakeholders understand operational trends and improve decision-making in the transportation and mobility sector.

📊 Objective

Identify ride demand patterns
Analyze earnings and fare trends
Monitor driver and trip performance
Understand top pickup/drop locations
Improve business insights with interactive visuals

🔧 Tools & Technologies

Power BI Desktop (Data modeling & visualization)
Power Query (Data cleaning & transformation)
DAX (Calculated measures)
Star Schema Modeling

🧹 Data Cleaning (Power Query)

Removed duplicates and null values
Standardized date/time format
Created new columns (Trip Duration, Day, Month, Hour)
Split pickup and drop location fields
Filtered invalid fare/distance records

🧠 Data Modeling

A star schema approach was used:
Fact Table – Trip details (fare, distance, time, driver ID)
Dimension Tables – Date, Customer, Driver, Location
Relationships were created to support smooth filtering.

🧮 DAX Measures Used

Total Trips
Total Revenue
Avg. Fare
Avg. Distance
Peak Hour Ride Count
Cancellation Rate
Driver Performance Score

📈 Dashboard Features

KPIs: Revenue, total trips, average fare
Interactive Maps: Pickup & drop hotspots
Line Charts: Daily & hourly demand trends
Bar Charts: City-wise & category-wise trips
Filters & Slicers: Ride type, city, time, driver
Navigation Buttons: Multi-page report flow
Tooltips: Additional trip insights

🎯 Business Insights

Identified peak ride hours and high-demand zones
Recognized top-performing drivers and routes
Highlighted revenue patterns by city/vehicle type
Improved understanding of customer behavior

📘 Conclusion

This Power BI project provides a robust analytical view of Uber operations, enabling data-driven decisions in the transportation industry. The dashboard helps understand demand cycles, optimize driver allocation, and enhance revenue strategies.

