# Delhivery Business case study
 Logistics Data Analysis

Introduction
Delhivery, India's leading and rapidly growing integrated player, has set its sights on creating the commerce operating system. They achieve this by utilizing world-class infrastructure, ensuring the highest quality in logistics operations, and harnessing cutting-edge engineering and technology capabilities. The Data team builds intelligence and capabilities using this data that helps them to widen the gap between the quality, efficiency, and profitability of their business versus their competitors.

Problem Statement:
Delhivery, India's leading logistics provider, aims to leverage its vast data infrastructure to enhance operational efficiency and outperform competitors. The objective is to process data from their engineering pipelines to:
  --> Clean and manipulate raw data to extract valuable features.
  --> Interpret the data to generate insights that support the development of forecasting models for improving logistics operations.
This analysis is expected to improve the company's quality, efficiency, and profitability through data-driven decision-making.


#Insights
--> The most common route type is Carting.
--> The top 3 source and destination states are Maharastra, Karnataka and Haryana.
--> The top 3 source and destination cities are Bengaluru, Mumbai and Gurgaon.
--> Most of the packages are sent and received within Bengaluru, Mumbai and Hyderabad but the most busiest corridor is Bhiwandi-Mumbai.
--> start_scan_to_end_scan and od_time_diff_hour are similar
--> Aggregated actual_time and aggregated osrm_time are not similar.
--> Aggregated actual_time and aggregated segment_actual_time are similar.
--> Aggregated osrm_distance and aggregated segment_osrm_distance are similar.
--> Aggregated osrm_time and aggregated segment_osrm_time are similar.

#Business Recommendations
--> Optimize resources for busiest corridors:
    While most packages are sent and received within Bengaluru, Mumbai and Hyderabad and the busiest corridor is Bhiwandi-Mumbai. So based on this, Delhivery should allocate additional resources such as warehouse, vehicles and manpower to manage the high shipment volume in this corridor more effectively.

--> Refine distance and time estimations:
    There is a significant difference between the actual time and the OSRM time (predicted time by the routing engine) across corridors. Therefore, the company should adjust the algorithm to improve prediction accuracy.

--> Promote FTL as faster than carting
    The company should emphasize the benefits of the Full Truck Load (FTL) route type as a faster delivery option compared to carting. By highlighting its speed advantages, FTL can be recommended to large organizations as a more efficient choice