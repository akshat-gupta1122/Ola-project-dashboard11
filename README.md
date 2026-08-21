# OLA Data Analyst Project

Hi, this is my OLA Data Analysis project. I made this project using SQL, Power BI, and Excel. In this project I analyzed OLA ride booking data to understand bookings, revenue, cancellations, and ratings.

---

## Tools Used
* Excel (for raw dataset check)
* SQL (for writing queries and solving questions)
* Power BI (for building interactive dashboard)

---

## Dataset Information
The dataset name is `Ola_Bookings_Dataset_1000.csv`. It contains following fields:
* Date & Time
* Booking_ID
* Booking_Status (Success, Cancelled by Customer, Cancelled by Driver, Driver Not Found)
* Customer_ID & Vehicle_Type (Auto, Prime Sedan, Prime SUV, Bike, eBike, Mini, etc.)
* Pickup_Location & Drop_Location
* V_TAT & C_TAT
* Booking_Value & Payment_Method (UPI, Card, Cash, Wallet)
* Ride_Distance_km
* Driver_Rating & Customer_Rating

---

## SQL Queries Solved
I wrote SQL queries to solve 10 key questions:
1. Retrieve all successful bookings.
2. Find average ride distance for each vehicle.
3. Get total number of cancelled rides by customers.
4. List top 5 customers who booked highest number of rides.
5. Get number of rides cancelled by drivers due to personal/car issues.
6. Find max and min driver ratings for Prime Sedan.
7. Retrieve all rides where payment was made using UPI.
8. Find average customer rating per vehicle type.
9. Calculate total booking value of rides completed successfully.
10. List all incomplete rides along with reason.

---

## Power BI Dashboard Features
Created interactive Power BI report with 5 main views/pages:
* **Overall View:** Shows Total Bookings (1000), Total Booking Value (697K), Booking Status Breakdown pie chart, and Ride Volume Over Time line chart.
* **Vehicle Type:** Analysis by vehicle category.
* **Revenue:** Payment method analysis and revenue insights.
* **Cancellation:** Reasons for ride cancellations by driver and customer.
* **Ratings:** Customer and driver ratings comparison.

---

## How to Run This Project
1. Import `Ola_Bookings_Dataset_1000.csv` into SQL database.
2. Run SQL script to see all query answers.
3. Open Power BI Desktop file to view interactive dashboard.

---
Thank you!
