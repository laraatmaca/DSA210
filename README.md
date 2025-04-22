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

## **Findings**
After analysis, key insights will be summarized, addressing questions such as:
- **Which cities and highways have the highest accident rates?**
- **Are accidents more frequent in certain months or seasons?**
- **How do speed limits and road conditions affect accidents?**
- **Are road safety policies reducing accident rates?**

## **Limitations and Future Work**
- Some accidents might be underreported, which could impact the accuracy of the findings.
- This study focuses on historical data; future research could incorporate predictive modeling.
- Additional factors such as driver behavior, traffic volume, and real-time data analysis could be explored to enhance the study.
