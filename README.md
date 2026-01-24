### Ride Booking Performance Revenue Analytics Dashboard Using Power BI

# Project Summary:-
This project is an End-to-End Power BI Analytics solution built on a 200,000+ row raw ride-booking dataset, designed to simulate a real-world ride-hailing business environment (similar to Uber/Ola).

The analysis focuses on **Revenue Performance, Operational Efficiency, Ride Cancellations, and CUstomer Behavior** using interactive Power BI dashboards.

The project covers the complete analytics lifecycle:
- Raw data understanding & cleaning.
- Data modeling & relationships.
- DAX measures & KPIs.
- Business insights & storytelling.

This dashboard helps stakeholders identify **Revenue Drivers, Operational Bottlenecks, and Customer Patterns** to support data-driven decision-making.

-----

# Dataset Description (Clean Data):-

- Total Rows: **200,000+**
- Total Columns: **20**
- Data Granularity: **Individual Ride-Level Transactions**
- Data Type: **Raw Data ("Ride_Booking_Raw.csv") containing missing values, duplicates, and inconsistent formats**.

The dataset represents ride bookings across **Multiple Cities, Vehicle Types, Payment Methods, and Booking Statuses**.

# # Columns Name(Clean Data):
- booking_id
- customer_id  
- city  
- vehicle_type  
- trip_distance_km
- trip_duration_min
- base_fare
- distance_fare
- total_fare
- Fare_Category
- payment_method
- booking_status (Completed / Cancelled / Customer_Cancelled / Driver_Cancelled)
- driver_id
- driver_rating
- customer_rating
- surge_applied
- discount_applied
- booking_date
- year
- month_name
- month_number
- booking_hour
- is_weekend
- cancellation_reason

-----

# Tools and Techniques Used:-
**Power BI**
- **Power Query** (Data Cleaning & Transformation).
- **DAX** (KPIs & Measures).
- **Star Schema Data Modeling**.
- **CSV Dataset (Raw Source Data)**.
- **Data Visualization**.

-----

# Business Objectives:-
- Analyze overall ride booking performance.
- Identify revenue-generating cities and vehicle types.
- Understand cancellation patterns and reasons.
- Measure operational efficiency.
- Improve customer and driver performance using ratings.
- Support strategic business decision-making.

-----

# KPIs Calculated:-
- Total Bookings
- Completed Rides
- Cancellation Rate (%)
- Total Revenue
- Average Ride Value
- Revenue By City
- Revenue By Vehicle Type

-----

# Key Analytical Insights:-
- **25–30% of Rides were Cancelled or Incomplete,** leading to "Revenue Leakage".  
- **Top 3 Cities Contributed ~50% of Total Revenue**.
- Premium vehicle types **(Sedan/SUV) generated higher average booking value**
- Peak hours showed **Higher Cancellations due to driver unavailability**
- Higher driver ratings correlated with **Better Ride Completion Rates**

-----

# Key Learnings:-
- Hands-on experience with **Large-Scale Datasets (200K+ rows)**.
- Practical understanding of **Power Query Data Cleaning**.
- Writing optimized **DAX Measures for Business KPIs**.
- Designing dashboards for **Business Stakeholders**.
- Translating raw data into **Actionable Insights**.

-----

# Project Structure:-
Ride Booking Performance & Revenue Analytics Dashboard
- "Business_Insights.md": Business Insights & Recommendations.
- "Ride_Booking_Raw.csv": Raw Dataset.
- "Ride Booking Revenue & Operations Dashboard (Template).pbit": Power BI Template.
- "Ride Booking Revenue & Operations Dashboard.pbix": Power BI Desktop File.
- "Ride Booking Revenue & Operations Dashboard.pdf": PDF Of Dashboard.
- "README.md": Project Documentation.





