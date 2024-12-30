# Railway-Analysis-
This repository contains mock train ticket data for National Rail services in the UK, spanning from January to April 2024. The dataset simulates a variety of train journeys, providing details such as ticket types, journey dates and times, departure and arrival stations, ticket prices, and other key attributes. It is designed for use in testing, data analysis, and simulation purposes related to the UK rail industry.
# Introduction 
This dataset has been analyzed using Power BI and presents an analysis of train tickets sold within a 4-month period (January to April 2024). The mock dataset simulates train ticket sales for journeys across the UK National Rail network.

The dataset includes tickets for various travel classes (Standard, First Class, and Off-Peak) and journeys between numerous departure and arrival stations. Tickets are categorized by type, journey date and time, train operators, and ticket status (e.g., Booked, Cancelled, Pending).

Tickets are either purchased directly or pre-booked online, reflecting two key sales channels. The analysis focuses on identifying trends in ticket sales, popular routes, and average ticket prices. It provides valuable insights for assessing ticket pricing strategies, passenger behavior, and service optimization.

This mock dataset is ideal for testing, visualizations, and simulations related to the UK's National Rail system.
# Problem Statement
The following questions are the recommended analysis
What are the most popular departure and arrival stations?

Which ticket types and classes generate the most revenue?

What are the main reasons for delays and cancellations?

Which days and times are the busiest for travel?

How does city-wise revenue and refund percentage vary?
# Data Source
This repository contains an analysis of a mock train ticket dataset sourced from Maven Analytics Playground. The dataset includes detailed information about train tickets sold for journeys across the UK National Rail network, covering the period from January to April 2024.
# Skills and Concepts Demonstrated
The following are skills and concepts demonstrated when working on this project
Transforming and cleaning data using Power Query Editor
Creating columns for calculations of sales and profit
Developing general DAX calculations
Designing dashboard for a cohesive view of key performance indicators
Data visualization
# Data Transformation
Changed all fields to the appropriate data types. Created new columns to calculate The city, Month name, Hour, Weekday, Time Period.
 ![image](https://github.com/user-attachments/assets/58fff272-6795-4366-b77d-20acea0fdf52)
# Data Analysis
Created DAX functions for aggregation and simple calculations
![image](https://github.com/user-attachments/assets/188b6f90-46cb-4ebf-9893-03de797872dd)

# Data Visualization
This dashboard provides a comprehensive analysis of railway ticket sales, uncovering valuable insights and highlighting opportunities to optimize performance. It identifies key periods to focus on for increasing ticket sales and revenue while providing actionable recommendations for strategic decision-making.
Dashboard 
![image](https://github.com/user-attachments/assets/af4c5a00-d8e0-47b2-b175-29c61e1740d6)
![image](https://github.com/user-attachments/assets/99d5d440-9530-4cf5-af85-574ce92200f3)
![image](https://github.com/user-attachments/assets/e608da4e-f192-4f21-9e4f-014556e620be)
# Key Insight 
Revenue Insights

Total Revenue: £742,000, with a net revenue of £703,000 after refunds.

Top Ticket Types:

Advance: £309,274

Off-Peak: £223,338

Anytime: £209,309

Station and Route Insights

Most Popular Departure Station: Manchester Piccadilly (5,650 bookings).

Top Arrival Destination: Birmingham New Street (7,742 bookings).

Busiest Route: Manchester Piccadilly to Liverpool Lime Street (4,628 trips).

Travel Insights

On-Time Performance: 86.82% of trips were punctual.

Peak Travel Hours: Evening peak (5 PM) saw the highest passenger count.

Common Delay Reasons: Weather, signal failure, and technical issues.

City-Wise Revenue

Top Cities by Revenue:

London: £458,494 (2.1% refund rate).

Liverpool: £135,274 (10.8% refund rate).
 KPIs Defined

Net Revenue: £703,000.

Ticket Sales: 31,653 total tickets sold, 1,880 cancelled.

On-Time Performance Rate: 86.82%.

# Reccomendations 
Based on the analysis, I recommend:

1. Improve Delay Management: Focus on mitigating weather and signal-related delays.

2. Optimize Routes: Increase capacity on popular routes like Manchester Piccadilly to Liverpool Lime Street.

3. Targeted Marketing: Promote advance ticket types and premium classes to increase revenue.

4. Enhance Refund Policies: Review high-refund cities like Liverpool to improve customer retention.

5. Expand Peak Services: Add more services during evening peak hours to accommodate demand.





