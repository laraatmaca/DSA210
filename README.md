# **Traffic Accident Trends in Turkey**

## **Motivation**
Traffic accidents are a major issue in Turkey, causing thousands of injuries and fatalities every year. Understanding accident patterns can help improve road safety measures, influence policy decisions, and reduce accident rates. By analyzing past traffic data, we can identify high-risk areas, seasonal trends, and common causes of accidents.

## **Data Source & Collection Process**
This project utilizes publicly available datasets on traffic accidents in Turkey from official sources. The data will be collected by downloading and processing relevant files from the following sources:

1. **Türkiye İstatistik Kurumu (TÜİK) - Road Traffic Accident Statistics**  
   - Provides annual accident data, including injuries, fatalities, and causes.  
   - Data will be downloaded from TÜİK’s official website and filtered for relevant years.  
   - [Dataset Link](https://data.tuik.gov.tr/Bulten/Index?p=Karayolu-Trafik-Kaza-Istatistikleri-2022-49513)  

2. **Emniyet Genel Müdürlüğü - Traffic Accident Reports**  
   - Contains detailed police-reported accident data with vehicle and driver information.  
   - Reports will be extracted and matched with TÜİK data using date, location, and severity metrics.  
   - [Traffic Report Link](https://trafik.gov.tr/istatistikler37)  

## **Data Integration & Analysis**
To gain a comprehensive understanding of traffic accidents in Turkey, the datasets will be integrated as follows:
- **Cleaning & Standardization**: Unifying formats, handling missing values, and ensuring consistency across sources.
- **Merging Data**: Accident reports will be enriched with road condition data by matching them based on location (city, highway, GPS coordinates) and time (year, month, day).
- **Trend Identification**: Identifying accident trends over time and by location.
- **Visualization**: Mapping accident hotspots and seasonal variations.
- **Factor Analysis**: Examining the effects of weather, road conditions, and speed limits on accident rates.

---

## **Phase 2 – Data Analysis & Findings**

###  TÜİK-Based Insights

#### Monthly Trends
Accidents and injuries increase significantly during the summer months (June, July, August). These months also correspond to the peak holiday season in Turkey.

#### Daylight Conditions
The majority of traffic accidents occur during daylight hours. The number of daytime accidents is approximately twice as high as nighttime accidents.

#### Hypothesis Test 1: Summer vs. Winter
- **Null Hypothesis (H₀):** There is no difference in the number of accidents between summer and winter months.
- **Alternative Hypothesis (H₁):** There is a significant difference.
- **Result:** p-value = 0.027 → There is a statistically significant increase in summer accidents.

#### Hypothesis Test 2: Daytime vs. Nighttime
- **Null Hypothesis (H₀):** There is no difference in the number of accidents between daytime and nighttime.
- **Alternative Hypothesis (H₁):** There is a significant difference.
- **Result:** p-value = 0.000 → Daytime accidents are significantly more frequent.

###  EGM-Based Insights (May, Feb, Dec 2024)

####  May 2023
- Urban areas had 4.1x more accidents than non-urban.
- Driver fault accounts for ~87% of total faults.
- Most involved vehicles: Passenger cars, motorcycles, pickups.

####  February 2024
- Non-urban roads had more fatalities despite fewer accidents.
- Cars and motorcycles dominate accident involvement.
- Driver fault is still major (~90%).

####  December 2024
- Over 30,000 injuries recorded; highest for winter months.
- Cars top the list again; motorcycles remain high-risk.
- Driver fault remains leading cause across all months.

###  Visual Evidence
All related graphics are stored under:

---

## **Limitations and Future Work**
- Some accidents might be underreported, which could impact the accuracy of the findings.
- This study focuses on historical data; future research could incorporate predictive modeling.
- Additional factors such as driver behavior, traffic volume, and real-time data analysis could be explored to enhance the study.

