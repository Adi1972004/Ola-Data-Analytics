# Ola-Data-Analytics

## 📌 Project Overview
This project analyzes **Ola Cab** booking data using **SQL** and **Power BI** to derive insights on ride volumes, revenue, cancellations, customer behavior, and driver performance.  

The dataset contains **100,000 records** of bookings with details such as:
- Booking status
- Vehicle type
- Ride distance
- Ratings
- Payment method
- Cancellation reasons

The goal is to create **interactive dashboards** and **SQL views** to help the business optimize operations and improve customer experience.

---

## 🗂 Dataset Information

| Column Name | Description |
|-------------|-------------|
| `Date`, `Time` | Booking date and time |
| `Booking_ID` | Unique ride identifier |
| `Booking_Status` | Success / Cancelled by Customer / Cancelled by Driver / Driver Not Found |
| `Customer_ID` | Unique customer ID |
| `Vehicle_Type` | Prime Sedan, Prime SUV, Mini, Auto, Bike, E-Bike, Prime Plus |
| `Pickup_Location` | Start point |
| `Drop_Location` | Destination |
| `V_TAT`, `C_TAT` | Vehicle & customer turnaround time |
| `cancelled_Rides_by_Customer` | Reason for customer cancellation |
| `cancelled_Rides_by_Driver` | Reason for driver cancellation |
| `Incomplete_Rides` | Yes / No |
| `Incomplete_Rides_Reason` | Reason why ride was incomplete |
| `Booking_Value` | Cost of ride |
| `Payment_Method` | Cash / UPI / Credit Card / Debit Card |
| `Ride_Distance` | Total distance travelled in KM |
| `Driver_Ratings` | Rating given to driver |
| `Customer_Rating` | Rating given by driver |

---

## 🎯 SQL Analysis Tasks
The SQL scripts create **views** and queries to answer 10 business questions:

1. Retrieve all successful bookings  
2. Find the average ride distance for each vehicle type  
3. Get the total number of cancelled rides by customers  
4. List the top 5 customers who booked the highest number of rides  
5. Get the number of rides cancelled by drivers due to personal and car-related issues  
6. Find the maximum and minimum driver ratings for Prime Sedan bookings  
7. Retrieve all rides where payment was made using UPI  
8. Find the average customer rating per vehicle type  
9. Calculate the total booking value of rides completed successfully  
10. List all incomplete rides along with the reason  

📂 **File:** `Ola_SQL_query.sql` contains all the SQL scripts.

---

## 📊 Power BI Dashboard Insights

### **Key Visuals**
- **Ride Volume Over Time** → Daily/weekly ride trends
- **Booking Status Breakdown** → % of successful vs cancelled rides  
- **Top 5 Vehicle Types by Ride Distance** → Most traveled vehicle categories  
- **Average Customer Ratings by Vehicle Type**
- **Cancelled Ride Reasons** (Customer vs Driver)
- **Revenue by Payment Method** → Cash, UPI, Credit Card comparison
- **Top 5 Customers by Total Booking Value**
- **Ride Distance Distribution Per Day**
- **Driver Ratings Distribution**
- **Customer vs Driver Ratings**

📂 **File:** `Ola_PowerBI_Dashboard.pdf` contains the dashboard snapshot.

---

## 📈 Summary of Key Metrics (July 2024)
- **Total Bookings:** 103,024  
- **Total Booking Value:** ₹35 Million  
- **Success Rate:** ~62%  
- **Cancellation Rate:** ~28% (Drivers + Customers)  
- **Top Paying Customer:** CID785112 with ₹8,025  
- **Average Ride Distance:** ~25 KM (varies by vehicle type)  
- **Best Rated Vehicle Type:** Prime SUV & E-Bike (Avg Rating: 4.01)  

---

## 🛠 Tools & Technologies
- **SQL** (MySQL)
- **Power BI** for dashboard visualization
- **Excel/CSV** for initial data cleaning
- **100,000 records dataset**

---

## 📂 Project Structure

Ola-Data-Analytics/
├── Ola_SQL_query.sql             # SQL queries and views for data analysis  
├── Ola_PowerBI_Dashboard.pdf     # Power BI dashboard snapshot/report  
├── OLA-Data-Analyst-Project.pdf  # Full project description and detailed insights  
└── README.md                     # Project documentation  



---

## 🚀 How to Run
1. **Database Setup**
   - Create a database `Ola`
   - Import the dataset into a table `bookings`
   - Execute the queries from `Ola_SQL_query.sql`

2. **Power BI**
   - Import the dataset into Power BI
   - Create visuals using insights listed above

---

## 📌 Insights & Business Recommendations
- **Reduce Cancellations**: Most cancellations by drivers occur due to *personal & car issues*, suggesting improvements in vehicle maintenance and driver scheduling.
- **Promote High Revenue Customers**: Offer loyalty rewards to top customers like CID785112 who significantly contribute to revenue.
- **Encourage UPI Payments**: UPI-based rides form a large chunk of transactions — explore Cashback offers.
- **Vehicle Performance**: Prime SUV and E-Bike received the highest ratings — market them more.

---

## 📧 Contact
**Author:** *Aditya Chandel*  
**Email:** ps2419707@gmail.com  


