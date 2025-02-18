# OLA Ride Data Analysis

## Project Overview
This project analyzes OLA ride data using SQL for data querying and Power BI for visualization.  
It aims to uncover insights into ride patterns, customer behavior, and operational metrics.

---

## Dataset Details
- **File Name:** `OLA_Ride_Data.csv`
- **Total Rows:** 100,000+
- **Total Columns:** 28
- **Key Features:**
  - `ride_id` - Unique identifier for each ride
  - `customer_id` - Unique customer identifier
  - `driver_id` - Unique driver identifier
  - `ride_status` - Completed, Canceled, or In-Progress
  - `vehicle_type` - Mini, Prime Sedan, Auto, Bike, etc.
  - `ride_distance_km` - Distance traveled
  - `payment_method` - Credit Card, Cash, Wallet, etc.
  - `customer_rating` - Rating given by the customer
  - `driver_rating` - Rating given by the driver
  - `cancellation_reason` - Reason for ride cancellation

---

## SQL Calculations & Insights
The following insights were derived from the dataset using SQL queries:

1. **Successful Bookings** – Retrieved all rides with the status "Completed."
2. **Average Ride Distance** – Calculated the average ride distance for each vehicle type.
3. **Canceled Rides by Customers** – Counted the number of canceled rides initiated by customers.
4. **Top 5 Customers by Ride Count** – Identified the top 5 customers who booked the highest number of rides.
5. **Driver Cancellations Due to Personal or Car Issues** – Identified and counted cancellations caused by drivers' personal issues or car breakdowns.
6. **Driver Ratings for Prime Sedan Rides** – Found the maximum and minimum driver ratings for Prime Sedan rides.
7. **Payment Methods Used** – Filtered rides based on specific payment methods used.
8. **Average Customer Ratings per Vehicle Type** – Calculated the average customer rating for each vehicle type.
9. **Total Revenue from Completed Rides** – Summed the total ride fare from successfully completed rides.
10. **Incomplete Rides** – Retrieved all incomplete rides and their respective cancellation reasons.

These calculations provide valuable insights into the ride data, helping to identify patterns, operational issues, and customer behavior.

---

## Power BI Visualizations & Insights
The Power BI dashboard offers a comprehensive set of visualizations to explore the OLA ride data. Below are some of the key insights provided by the dashboard:

1. Ride Volume Over Time – Trends in ride bookings by month/day.
2. Booking Status Breakdown – Percentage of completed, canceled, and in-progress rides.
3. Top 5 Vehicle Types by Ride Distance – Identifies the most used vehicle types.
4. Average Customer Ratings by Vehicle Type – Evaluates customer satisfaction.
5. Canceled Ride Reasons – Shows why rides were canceled.
6. Revenue by Payment Method – Analyzes payment method usage.
7. Top 5 Customers by Total Booking Value – Identifies high-value customers.
8. Ride Distance Distribution – Shows ride distance patterns.
9. Driver Ratings Distribution – Examines how drivers are rated.
10. Customer vs. Driver Ratings – Compares customer and driver rating trends.

### Power BI Dashboards:

- ![Dashboard Image 1. Overall](Overall.png)  

- ![Power BI Dashboard Image 2](path-to-image2.png)  
  *Description of what the dashboard image represents, e.g., "Revenue by Payment Method."*

---
