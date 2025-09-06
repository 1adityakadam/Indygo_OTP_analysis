# 🚍  IndyGo On-Time Performance (OTP) Dashboard

<img width= 1080 src='https://github.com/user-attachments/assets/663c86d8-43e7-4ed6-adb8-9fa2894abb84'><br>



📌 Business Objective

The objective of this project was to design and develop a Power BI dashboard that analyzes IndyGo’s On-Time Performance (OTP). By leveraging GPS and Automatic Passenger Counter (APC) data, the dashboard measures service reliability and provides real-time and historical insights into trip adherence.

This initiative supports IndyGo’s broader open data vision by improving:
  * Transparency: Enabling public access to OTP data.
 *  Operational efficiency: Helping IndyGo teams identify problem areas.
  * Decision-making: Providing planners and stakeholders with actionable insights to optimize routes and schedules.

Key business questions addressed:

 * What is the overall OTP by day of service (Weekday, Saturday, Sunday)?
 * How does OTP vary across route categories (rapid transit, frequent, basic, coverage)?
 * What are the 12-month OTP trends at system and route levels?
 * How does OTP change across timeframes (monthly, bid period, rolling five weeks)?
 * How does OTP differ during peak vs. non-peak hours?

✅ Results and Impact

The final dashboard delivered the following outcomes:

 * Comprehensive OTP Trends
Visualized weekly, monthly, and yearly performance with category breakdowns (On-Time, Early, Late).

 * Service Category Insights
Rapid services performed best (73.01% OTP), followed by Frequent (62.03%) and Basic (53.99%)


 * Day of Service & Peak Analysis
Identified clear differences between weekday vs. weekend OTP, and higher delays during peak hours compared to off-peak

 * Route-Level Performance
Top 10 routes were highlighted using treemaps, showcasing high performers (e.g., East 16th St, Nora, Broad Ripple) and underperformers (e.g., Mars Hill, East 21st St)

 * Data-Driven Recommendations
Addressed Power BI file size challenges through preprocessing (null handling, column filtering, parquet conversion), improving scalability and performance

 * Future Enhancements
Proposed modular dashboards with iframes, predictive modeling for delays, and natural language queries for user-friendly interactions


🛠️ Tech Stack

 * Power BI: Data modeling & visualization

 * DAX: Business rules (OTP categorization, peak vs. non-peak logic, service classification)

 * Data Processing: Python + Parquet for preprocessing & optimization

 * Data Sources: GPS Trackers, APCs, Scheduling Data

🌐 Relevant Links

 * IndyGo official site: indygo.net

 * IndyGo stakeholder engagement: Transit is Essential


✅ Key Results:

* Identified service category differences (Rapid services achieving 73% OTP vs. Basic services at 54%)

* Highlighted peak-hour delays and weekday vs. weekend reliability

* Improved data pipeline efficiency by addressing Power BI file size and quality challenges

This dashboard supports IndyGo’s open data vision, improving transparency, operational efficiency, and decision-making for public transit in Indianapolis.

#PowerBI #DataAnalytics #PublicTransit #BusinessIntelligence
