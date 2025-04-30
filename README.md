🌾 District-Level Agricultural Analysis – Power BI Project Report
1. Project Title:
District-Level Agricultural Performance Analytics Using Power BI
________________________________________
2. Executive Summary:
This Power BI project aims to analyze district-level agricultural data to identify production trends, crop performance, irrigation coverage, and regional disparities in farming practices across Indian districts. The dashboard provides policymakers and researchers with a comprehensive view to support data-driven decisions for sustainable agriculture.
________________________________________
3. Objectives:
•	Analyze crop-wise and district-wise production trends.
•	Identify high and low-performing agricultural districts.
•	Study irrigation coverage and land use patterns.
•	Provide actionable insights for agricultural planning and resource allocation.
________________________________________
4. Dataset Description:
•	Source: ICRISAT District-Level Dataset
•	Records: Multi-year panel data for Indian districts
•	Key Fields:
o	State, District
o	Year, Season
o	Crop, Area Sown, Production, Yield
o	Irrigated Area, Rainfall, Fertilizer Use, Population
________________________________________
5. Data Preparation & Modeling:
•	Cleaned missing and inconsistent values using Power Query.
•	Created a star schema with:
o	Fact Table: Crop Production Data
o	Dimension Tables: Districts, Crops, Time, Weather
•	Created DAX measures including:
o	Total Production
o	Average Yield
o	Irrigation Ratio = Irrigated Area / Total Area
o	Fertilizer Usage per Hectare
________________________________________
6. Dashboard Features:
🌱 Crop Production Overview
•	Line chart showing production trends over years by crop and state
•	KPI indicators: Total Production, Avg. Yield, Irrigated Area %
🗺️ District-Level Map Visualization
•	Choropleth map of India displaying:
o	Yield per hectare
o	Irrigation coverage
o	Fertilizer usage intensity
🥦 Crop Comparison
•	Bar charts showing top crops by production and yield
•	Multi-year performance trend lines
🌦️ Weather Impact Analysis
•	Rainfall vs. Yield scatter plot
•	Conditional formatting to show years of low rainfall and low yield
________________________________________
7. Key Insights:
•	Yield Variability: Districts in southern India tend to have more stable yields over time.
•	Irrigation Gaps: Some high-yield districts still rely on rainfed agriculture.
•	Crop Performance: Rice and Wheat dominate production, but Maize and Pulses show promising yield increases.
•	Rainfall Dependency: Certain crops exhibit strong yield sensitivity to rainfall fluctuations.
•	Fertilizer Impact: Overuse of fertilizers is not strongly correlated with higher yields in all cases—optimal usage matters.
________________________________________
8. Recommendations:
1.	Target Irrigation Investment in high-potential but low-irrigated districts.
2.	Promote Climate-Resilient Crops in rainfall-dependent areas.
3.	Focus on Balanced Fertilizer Use to optimize input cost vs. yield.
4.	Use Yield Data for Crop Diversification Planning in mono-crop districts.
5.	Deploy Agricultural Extension Programs in low-yield but high-resource districts.
________________________________________
9. Conclusion:
This Power BI dashboard offers a scalable and interactive solution for visualizing complex agricultural data at the district level. It equips stakeholders with real-time insights to drive policy, enhance productivity, and ensure sustainability in agriculture.

