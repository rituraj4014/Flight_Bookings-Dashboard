# Flight_Bookings-Dashboard
✈️ Flight Booking & Travel Data Analysis Dashboard (Power BI)

📌 Project Overview

This project presents an end-to-end Flight Booking & Travel Data Analysis Dashboard built using Microsoft Power BI. The goal of the project is to analyze flight booking data and extract meaningful business insights related to ticket pricing, passenger demographics, airline performance, travel classes, payment methods, and travel distance.

The dashboard is designed to help stakeholders understand booking behavior, revenue contribution, and customer preferences, enabling better decision-making in the airline and travel domain.

🎯 Project Objectives

Build a fully interactive business intelligence dashboard

Analyze flight bookings and ticket price trends

Compare airline-wise and city-wise ticket revenue

Understand passenger demographics and age distribution

Evaluate travel class preferences

Analyze payment method usage and booking patterns

Apply real-world data analytics and visualization practices

🧰 Tools & Technologies Used

Microsoft Power BI – Dashboard creation and visualization

Power Query – Data cleaning and transformation

DAX (Data Analysis Expressions) – KPI and measure calculations

Excel / CSV Dataset – Data source

Data Modeling – Relationship management and schema design

📊 Key Performance Indicators (KPIs)

Total Bookings: 500

Total Ticket Price: 348.88K

Average Passenger Age: 37.54 years

Total Distance Covered: 1M km

Average Flight Duration: 3.1 hours

Average Ticket Price: 697.77

📈 Dashboard Features & Visualizations
🔹 KPI Cards

Number of bookings

Total ticket revenue

Average passenger age

Total travel distance

Average flight duration

Average ticket price

🔹 Analytical Visuals

Ticket Price by Airline – Compare revenue across airlines

Ticket Price by Departure City – City-wise pricing analysis

Ticket Price by Travel Class – Economy, Business, First, Premium Economy

Ticket Price by Payment Method – Card, UPI, Net Banking, Wallet, Cash

Bookings by Payment Method – Customer payment preferences

Passenger Age Distribution (Bins) – Revenue by age group

🔹 Interactivity

Dynamic filters and slicers

Drill-down and cross-filtering for deeper analysis

🔄 Data Cleaning & Transformation

Performed using Power Query:

Removed null and duplicate records

Corrected and standardized data types

Cleaned airline, city, and payment method names

Created calculated columns for analysis

Optimized dataset for better performance

🧠 DAX Measures Used (Examples)

Total Bookings = COUNT(Bookings[Booking_ID])

Total Ticket Price = SUM(Bookings[Ticket_Price])

Average Ticket Price = AVERAGE(Bookings[Ticket_Price])

Average Passenger Age = AVERAGE(Bookings[Passenger_Age])

Total Distance = SUM(Bookings[Distance_km])

Average Flight Duration = AVERAGE(Bookings[Flight_Duration])

📌 Key Business Insights

Economy class generates the highest ticket revenue

Card and UPI are the most preferred payment methods

Certain airlines dominate ticket revenue share

Major revenue contribution comes from middle-aged passengers

Ticket prices vary significantly by departure city and airline

🔗 How to Run the Project
✅ Prerequisites

Install Microsoft Power BI Desktop
👉 https://powerbi.microsoft.com/desktop/

🟢 Steps

Clone the repository:

git clone https://github.com/your-username/Flight-Booking-Analysis.git


Open Power BI Desktop

Click File → Open

Select Flight_Booking_Dashboard.pbix

If prompted, reconnect the dataset from the Dataset/ folder

🚀 Future Enhancements

Add time-based analysis (daily / monthly trends)

Integrate SQL database or live data sources

Implement forecasting and predictive analytics

Optimize dashboard for mobile view

Publish to Power BI Service with scheduled refresh

👤 Author

Ritu Raj
📊 Aspiring Data Analyst
💡 Skills: Power BI | SQL | Excel | Python
📧 Email: rituraj4014@gmail.com
