Project Overview

This project analyzes real-world Road Traffic Accident data to identify key drivers of accident severity, including temporal factors, vehicle types, environmental conditions, and driver characteristics.

The dashboard supports data-driven decision-making by evaluating how time of day, vehicle category, road surface, weather conditions, lighting, and driving experience influence serious and fatal accident outcomes.

Objectives

Evaluate the impact of time of day on accident severity

Analyze how vehicle type influences fatal and serious injuries

Study the role of driving experience in crash outcomes

Examine the effect of road surface and weather conditions

Identify vulnerable road users and high-risk segments

Develop an interactive dashboard for traffic safety decision-making

Dataset Information

Source: Kaggle – Road Traffic Accident Dataset
Domain: Urban Transportation & Public Safety
Geographic Coverage: Addis Ababa
Time Period: 2017–2020
Structure: Each row represents one recorded accident
Tool Used: Google Sheets

Data Dictionary
Column Name	Description	Data Type
Accident_Severity	Accident outcome (Slight, Serious, Fatal)	Categorical
Driving_Experience	Experience level of driver	Categorical
Type_of_Vehicle	Vehicle category involved in accident	Categorical
Day_of_Week	Day accident occurred	Categorical
Weather	Weather condition at time of accident	Categorical
Road_Surface	Surface condition (Dry, Wet, Snow, Flood, etc.)	Categorical
Light_Condition	Lighting situation during accident	Categorical
Road_User_Type	Type of casualty (Driver, Passenger, Pedestrian)	Categorical
Cause_of_Accident	Primary reported cause (e.g., No Distancing)	Categorical
Number_of_Casualties	Total casualties per accident	Integer
Data Cleaning & Preparation

Standardized categorical fields (vehicle type, weather, severity labels)

Removed extra spaces and corrected inconsistent text entries

Handled missing values by labeling as “Unknown” where appropriate

Verified severity categories remain within defined classes

Grouped driving experience into consistent bands

Created calculated severity percentages (Fatal %, Serious %, Slight %)

Structured dataset for pivot-based analysis and dashboard integration

Key KPIs
KPI	Value
Total Accidents	12,316
Total Casualties	19,067
Serious Accident %	~14%
Fatal Accident %	~1%
Slight Injury %	~84%
Most Common Cause	No Distancing

The severity distribution highlights that while slight injuries dominate numerically, serious and fatal accidents represent high-impact safety risks.

Dashboard Components
Accident Severity Distribution

Shows overall composition of Slight, Serious, and Fatal accidents.

Vehicle Type vs Injury Severity (Radar Chart)

Analyzes how different vehicle categories contribute to accident severity.

Severity by Time of Day

Identifies high-risk temporal windows.

Vulnerability of Road Users

Compares severity exposure across drivers, passengers, and pedestrians.

Severity Risk vs Driving Experience (Bubble Chart)

Examines relationship between experience level and fatal/serious outcomes.

Accident Count by Road Surface

Analyzes infrastructure-related accident frequency.

Weather Condition Analysis

Shows accident distribution under different environmental conditions.

Light Condition Analysis

Evaluates how visibility impacts severity outcomes.

Key Insights

Slight injuries dominate total accidents, but serious and fatal crashes cluster under specific high-risk conditions.

Night-time driving increases the likelihood of severe outcomes.

Heavy vehicles are disproportionately associated with fatal accidents.

Poor road surface and adverse weather amplify severity risk.

Pedestrians and passengers show higher vulnerability in severe crashes.

“No distancing” is identified as the most common accident cause.

Risk is concentrated in specific combinations of time, vehicle type, and environmental conditions.

Recommendations

Increase enforcement during high-risk night-time periods

Strengthen heavy vehicle regulation and compliance checks

Improve road surface maintenance and lighting infrastructure

Implement targeted driver awareness and training programs

Focus safety interventions on vulnerable road users

Apply risk-based resource allocation using dashboard insights

Limitations

Dataset limited to one city (Addis Ababa)

Snapshot data (no continuous time-series modeling)

No geospatial mapping included

Observational analysis (cannot infer causality)

Lack of behavioral detail such as exact speed or intoxication level

Conclusion

Accident severity is not random — it is concentrated under identifiable environmental, behavioral, and vehicle-related conditions.

This dashboard enables structured, severity-focused analysis and supports strategic decision-making in traffic enforcement, infrastructure planning, and public safety policy implementation.

By applying targeted, data-driven interventions, authorities can reduce serious and fatal accident rates and improve overall road safety outcomes.