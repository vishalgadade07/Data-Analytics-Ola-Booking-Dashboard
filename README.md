# Data-Analytics-Ola-Booking-Dashboard

🪜 Step 1 — Project Introduction

Say:

“This is my OLA Data Analytics Dashboard. I built this using Excel, SQL, Power Query, and Power BI to analyze booking, revenue, cancellation, and rating data for the month of July 2024.”

Purpose:

“The goal was to understand booking trends, customer and driver behavior, and find key insights that can help improve business decisions.”

🪜 Step 2 — Data Preparation (Excel)

Say:

“I started by cleaning the raw data in Excel — removed duplicates, handled missing values, and ensured consistent date formats.
For example, I used Excel filters and conditional formatting to detect errors and standardize values.”

Reason:

“Clean data ensures accuracy before loading into SQL or Power BI.”

🪜 Step 3 — SQL Analysis

Say:

“Next, I used SQL to perform data analysis and queries — like finding total bookings, top customers, and most cancelled reasons.
I also created views in SQL to save complex queries for quick future analysis.”

Example line:

“For example, I created a view to calculate total success and cancellation bookings by vehicle type — this helped me directly import summarized data into Power BI.”

🪜 Step 4 — Power Query (Data Transformation)

Say:

“Then I used Power Query in Power BI for additional transformations — like changing data types, merging multiple tables, renaming columns, and removing unnecessary rows.”

Reason:

“Power Query helps automate data cleaning — so when data updates, Power BI refreshes automatically.”

🪜 Step 5 — DAX Measures Creation

Say:

“I created several DAX measures for key KPIs like:

TotalBookings = COUNT(Booking_ID)

TotalSuccess = COUNTROWS(FILTER(...))

TotalCancellations = COUNTROWS(FILTER(...))

CancellationRate = DIVIDE(TotalCancellations, TotalBookings) * 100”

Reason:

“This allowed me to calculate performance metrics dynamically across different filters.”

🪜 Step 6 — Dashboard Design in Power BI

Say:

“Finally, I designed an interactive dashboard with five pages, each focusing on a different business aspect.”

🔹 Dashboard Pages Explanation (What to Say)
1️⃣ Overall Page

“Shows total bookings (1,03,024), total value (35M), and overall booking trend.
I added a pie chart to show booking status breakdown — success, canceled by driver, canceled by customer, etc.
The line chart shows booking trends over the month — useful for identifying daily fluctuations.”

2️⃣ Vehicle Type Page

“This compares performance across different vehicle types — Prime Sedan, SUV, Mini, Auto, Bike, etc.
It includes total and success booking values, average and total distance travelled.
Helps management see which vehicle type performs best.”

3️⃣ Revenue Page

“This focuses on revenue by payment methods — cash, UPI, and cards.
Also shows top 5 customers and daily revenue patterns.
From this, we can see most customers prefer cash and UPI payments.”

4️⃣ Cancellation Page

“Breaks down cancellation reasons for both customers and drivers using pie charts.
Also displays total bookings, success bookings, and cancellation rate (28.1%).
Helps identify areas to reduce cancellations.”

5️⃣ Ratings Page

“Shows driver and customer ratings for each vehicle type.
All ratings are between 3.98 and 4.01 — indicating overall good service quality.”

🪜 Step 7 — Key Insights (Say at End)

Say confidently:

“From this dashboard, I found:

Success rate is around 62%.

Main cancellation reason: Driver not moving towards pickup location.

Cash and UPI are dominant payment methods.

Prime Sedan and E-Bike have slightly better ratings.”

🪜 Step 8 — Final Statement (Project Impact)

Say:

“This dashboard helps OLA management track overall performance, identify problem areas, and make quick, data-driven decisions.
I designed it to be dynamic, so whenever new data is added, insights update automatically.”

💡 Quick Tips When Speaking:

Keep tone confident and simple.

Use transition lines like:

“Now moving to the next page…”

“Here we can clearly see…”

“The reason I added this chart is…”

“This insight can help improve business decisions.”
