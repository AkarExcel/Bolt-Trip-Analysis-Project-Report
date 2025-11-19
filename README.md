## Bolt Trip Analysis Project Report
### Executive Summary
This project investigates Bolt Nigeria’s trip data for the period of September 1 to September 30, with the aim of improving operational efficiency, revenue performance, and customer experience. Using the PPDAC analytical framework and Power BI for data modeling and visualization, the study evaluates trip patterns, rider behavior, and location-based demand across the company’s service ecosystem.
The analysis reveals that Bolt completed approximately 104 thousand trips, generating a total booking value of about 388.4 million naira. The average trip produced about 3,700 naira in revenue, with most trips covering short urban distances of roughly 1 kilometer and lasting an average of 16 minutes. These metrics indicate that Bolt’s business model in Nigeria is largely driven by high frequency, short distance mobility in dense urban centers.
Customer behavior shows a strong preference for daytime travel, with daytime trips nearly doubling nighttime trips. Payment patterns remain predominantly cash based, accounting for about 67 percent of all transactions. This suggests limited adoption of digital payment options and highlights an opportunity for Bolt to promote wallet usage through targeted incentives.
Spatial analysis identifies Kosofe as the dominant mobility hub, serving as both the most frequent pickup and dropoff location. Other high demand zones include Eko Atlantic, Lekki, Ikotun, and Ogba. These hotspots align with commercial and residential activity centers and form the backbone of Bolt’s operational network.
Vehicle category comparisons show that Bolt Premium generates the highest booking value and records the highest number of pickups. Despite the higher cost of premium services, customer preference appears to favor comfort and reliability. Average booking amounts, however, remain consistent across vehicle types due to uniform pricing structures.
Overall, the project provides actionable insights for optimizing driver allocation, strengthening surge pricing strategies, increasing digital payment adoption, and refining service offerings. The Power BI dashboard developed in this study offers Bolt Nigeria a dynamic tool for ongoing performance monitoring and data driven decision making.
 
This executive analysis demonstrates the significant value of business intelligence in transforming raw operational data into strategic knowledge for improving transportation services at scale.

### Problem
Urban mobility platforms in Nigeria operate in a complex environment shaped by population growth, infrastructural constraints, and evolving customer expectations. Bolt Nigeria, a major ride hailing operator, aims to optimize operational performance and strengthen its competitive position. To achieve this, the company seeks a deeper understanding of rider behavior, revenue patterns, trip characteristics, and location-based demand.
The core problem addressed in this project is how Bolt can use its trip data to improve decision making in the areas of driver allocation, revenue optimization, customer satisfaction, and operational efficiency.
This analysis focuses on answering the following key business questions:
• How many trips were completed during the period under review
• What revenue was generated across all bookings
• What is the average revenue per trip
• How far do customers travel on average
• What is the average trip duration
• Which vehicle category contributes most to financial performance
• Which pickup and dropoff locations attract the highest demand
• What behavioral patterns exist across payment types, time of day, and trip types

### Plan
The project uses the PPDAC framework to ensure a structured approach to answering the problem.
The plan consists of the following steps:
1.	Import the Bolt trip dataset and the location table into Power BI.
2.	Inspect and clean the data to correct inconsistencies in date formats, location IDs, distance values, and timestamps.
3.	Derive new fields including Pickup Date, Pickup Hour, Trip Time, and Day or Night classification.
4.	Build DAX measures aligned with business KPIs (total bookings, total revenue, average revenue, total distance, average distance, average duration).
5.	Model relationships between fact and dimension tables for accurate filtering and location matching.
6.	Develop interactive dashboards that visualize trip patterns by day, trip type, payment type, vehicle type, and location.
7.	Conduct comparative analysis across districts and categories to identify trends, operational bottlenecks, and high value zones.


### Data
The dataset contains fields such as:
• Trip ID
• Pickup and dropoff timestamps
• Trip distance in kilometers
• Fare amount and surge fee
• Pickup and dropoff location IDs
• Vehicle type
• Payment type
A supplementary location table provides the names associated with each location ID.
Key calculated measures include:
• Total Bookings
• Total Booking Value
• Average Booking Amount
• Total Trip Distance
• Average Trip Distance
• Average Trip Duration
• Farthest Trip
• Most Frequent Pickup Point
• Most Frequent Dropoff Point
The dataset covers the period from September 1 to September 30, providing a full month view of Bolt operations.
Data transformation steps involved cleaning timestamps, converting distance measures, generating time based categories, and establishing active and inactive relationships for location analysis.

### Analysis
Trip Volume and Revenue
The system completed about 104 thousand trips in the period. These trips generated a total booking value of about 388.4 million naira, which marks strong operational activity. The average booking amount stood at about 3,700 naira, showing consistent fare behavior across vehicle types and days.

Trip Distance and Duration
The total distance covered was 56 thousand kilometers, with an average distance of 1 kilometer per trip. This confirms that Bolt operates primarily within short distance urban environments. Average trip duration was 16 minutes, which aligns with dense city commuting patterns.
 
Temporal Patterns
Daytime trips accounted for about 68 thousand, while night trips totaled about 36 thousand. This reinforces the typical demand cycle where work related and daytime economic activities drive mobility needs.  
Daily booking trends show fluctuations shaped by weekdays, weekends, and possible external events. These trends are crucial for demand forecasting and driver deployment.

Payment Behavior
Cash payments accounted for about 67 percent, while wallet payments represented about 32 percent. This illustrates the limited adoption of digital payment channels in the local market, creating room for incentives to shift customers toward electronic payments.
 
Location Based Demand
Kosofe emerged as both the most frequent pickup and most frequent dropoff location, demonstrating its central role in the mobility network. Other high demand locations include Eko Atlantic, Lekki, Ikotun, and Ogba. These are economically active or densely populated zones.
The farthest trip recorded was Ogudu to Civic Centre, a distance of about 23.2 kilometers. This demonstrates occasional long distance activity within the otherwise short trip ecosystem.
 
Vehicle Category Performance
Among all categories, Bolt Premium generated the highest booking value at about 145.9 million naira, supported by high trip volume. Despite this, average booking amounts across categories remained similar, approximately 3,700 naira. This indicates pricing stability across the fleet.
Premium vehicles also recorded the highest number of pickups, showing a strong customer preference for comfort based options.

Operational Insight Summary
• The market is driven by short trips and short durations
• Demand is strongly localized in specific districts
• Cash usage is high and presents an opportunity for digitization
• Premium vehicles outperform other categories
• Daytime activity dominates the operational landscape

### Conclusion
This project demonstrates that Bolt Nigeria operates within a high demand, short distance mobility environment shaped by dense urban activity and strong location-based patterns. The data shows consistent revenue performance, predictable daily trip cycles, and concentrated demand in key districts such as Kosofe, Lekki, and Eko Atlantic. These findings provide a foundation for practical operational improvements.
The heavy reliance on cash transactions highlights a gap in digital payment adoption. Bolt can address this by offering wallet incentives, loyalty rewards, and integrated promotional pricing that encourages users to shift from cash to electronic payments. This would reduce cash handling risk, improve driver payment flow, and strengthen financial transparency.
The dominance of short trips and 16-minute average durations suggests that Bolt should optimize driver positioning in micro mobility clusters rather than spreading resources evenly across districts. Concentrating drivers in high traffic zones during peak hours would reduce wait times, increase completed trips, and improve customer satisfaction.
Vehicle category analysis shows that Bolt Premium is a strong performer. This insight supports expanding the availability of Premium vehicles in high demand areas and adjusting pricing strategies to reflect customer preference for comfort. A targeted expansion of Premium in districts like Kosofe and Lekki could increase overall revenue without raising operating costs.
Finally, the location based patterns provide a clear roadmap for operational planning. Kosofe’s role as the central hub indicates where driver supply, marketing efforts, and surge pricing strategies should be prioritized. Long distance trips, though infrequent, highlight additional pricing opportunities for inter district routes.
Overall, the evidence shows that Bolt can significantly improve efficiency and profitability by aligning its operations with the behavioral, temporal, and spatial patterns observed in the data. The Power BI dashboard created for this project equips management with a dynamic tool for monitoring performance and making continuous data driven decisions.

