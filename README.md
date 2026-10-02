# flight-delay-operational-dashboard
Power BI dashboard analyzing flight delays, operational performance, delay causes, airports, airlines, and weather patterns.
# Flight Delay Operational Dashboard

## Project Overview

The Flight Delay Operational Dashboard is a Power BI project developed to analyze flight delay patterns and operational performance across airlines, airports, states, months, days, and weather conditions.

The dashboard provides an interactive view of key flight performance indicators and helps identify major operational factors contributing to flight delays.

## Problem Statement

Flight delays can negatively impact passenger satisfaction, airline operations, resource utilization, and overall service efficiency. This project analyzes flight data to identify delay patterns, high-risk operational areas, and major causes of flight disruptions.

## Project Objective

- Measure overall flight delay and on-time performance.
- Identify airports and airlines with higher delay rates.
- Analyze monthly and day-of-week delay patterns.
- Identify major causes of flight delays.
- Analyze the relationship between weather conditions and departure delays.
- Generate actionable insights to support operational planning and efficiency.

## Dataset Used

A synthetic dataset containing **25,000 flight records** was used for the analysis.

The dataset contains information related to:

- Flight details
- Airlines
- Origin and destination airports
- Origin and destination states
- Flight distance
- Scheduled and actual departure times
- Departure delays
- Scheduled and actual arrival times
- Arrival delays
- Flight delay status
- Delay causes
- Weather conditions

### Important Columns

| Column | Description |
|---|---|
| FlightID | Unique flight identifier |
| Date | Flight date |
| DayOfWeek | Day on which the flight operated |
| Month | Month of operation |
| Airline | Operating airline |
| OriginAirport | Departure airport |
| OriginState | State of departure airport |
| DestAirport | Destination airport |
| DestState | Destination state |
| Distance_Miles | Flight distance |
| ScheduledDepTime | Scheduled departure time |
| ActualDepTime | Actual departure time |
| DepDelay_Min | Departure delay in minutes |
| ScheduledArrTime | Scheduled arrival time |
| ActualArrTime | Actual arrival time |
| ArrDelay_Min | Arrival delay in minutes |
| IsDelayed | Indicates whether the flight was delayed |
| DelayCause | Primary cause of delay |
| WeatherCondition | Weather during flight operation |

## Tools & Technologies

- **Microsoft Power BI**
- **Power Query**
- **DAX**
- Data Cleaning & Transformation
- Data Visualization
- Business Intelligence

## Project Structure

```text
flight-delay-operational-dashboard/
│
├── images/
│   └── Flight Delay Operational Dashboard.png
│
├── PowerBI/
│   └── Flight Delay Operational Dashboard.pbix
│
└── README.md
```

## Methodology

The project followed a structured data analytics workflow:

**Raw Flight Data**  
↓  
**Data Validation & Cleaning**  
↓  
**Data Transformation**  
↓  
**DAX Measures & KPI Creation**  
↓  
**Exploratory Data Analysis**  
↓  
**Interactive Dashboard Development**  
↓  
**Insights & Recommendations**

Power Query was used for data validation and transformation, while DAX was used to create key performance indicators and analytical measures. The data was then analyzed across airports, airlines, months, states, delay causes, weather conditions, and days of the week.

## Key Performance Indicators

| KPI | Result |
|---|---:|
| Total Flights | **25K** |
| Delay Rate | **24%** |
| On-Time Performance | **76%** |
| Average Departure Delay | **12.8 minutes** |

## Dashboard Preview

![Flight Delay Operational Dashboard](images/Flight%20Delay%20Operational%20Dashboard.png)

## Key Findings

### 1. Overall Flight Performance

- **25,000 flights** were analyzed.
- **24% of flights experienced delays**.
- **76% of flights operated on time**.
- Average departure delay was **12.8 minutes**.

### 2. Top Origin Airports by Delay Rate

- **EWR — 42%**
- **LGA — 35%**
- **ORD — 32%**
- **ATL — 30%**
- **JFK — 28%**

The highest-delay airports show substantially higher delay rates than the overall **24%** benchmark.

### 3. Monthly Delay Rate

- **July — 31%**
- **December — 31%**
- **August — 29%**
- **June — 27%**
- **January — 26%**
- **October — 16%**

The difference between the highest and lowest monthly delay rates was **15 percentage points**.

### 4. Flight Delay Causes

- **Weather — 35.55%**
- **Carrier — 21.73%**
- **NAS (Air Traffic) — 16.91%**
- **Late Aircraft — 13.08%**
- **Other — 7.07%**
- **Security — 5.65%**

Weather was the largest recorded cause of flight delays.

### 5. Delay Rate by Airline

- **Spirit — 43%**
- **Frontier — 39%**
- **JetBlue — 35%**
- **United — 33%**
- **American — 32%**
- **Southwest — 31%**
- **Delta — 27%**
- **Alaska — 25%**

The difference between the highest and lowest observed airline delay rates was **18 percentage points**.

### 6. Delay Rate by Origin State

- **New Jersey — 42%**
- **Illinois — 32%**
- **New York — 31%**
- **Georgia — 30%**
- **California — 26%**
- **Massachusetts — 26%**
- **Pennsylvania — 25%**

This highlights geographic variation in operational performance.

### 7. Average Departure Delay by Weather

| Weather Condition | Average Delay |
|---|---:|
| Storm | **73.6 min** |
| High Winds | **73.5 min** |
| Fog | **71.6 min** |
| Snow | **71.1 min** |
| Rain | **15.6 min** |
| Clear | **11.4 min** |
| Cloudy | **9.5 min** |

Severe weather conditions were associated with substantially higher average departure delays.

### 8. Delay Rate by Day of Week

- Highest delay rate: **25%**
- Lowest delay rate: **23%**
- Friday and Sunday: **25%**
- Monday: **23%**

Day-of-week differences were relatively small compared with weather, airport, airline, and seasonal factors.

## Business Insights

The analysis identified several important operational patterns:

- Delay performance is concentrated at specific origin airports.
- Weather is the largest recorded delay cause.
- Severe weather conditions are associated with substantially longer departure delays.
- Certain months experience considerably higher delay rates.
- Airline delay performance varies significantly.
- Geographic differences exist across origin states.
- Day-of-week differences are comparatively small.

## Business Recommendations

1. Prioritize operational reviews at high-delay airports such as **EWR, LGA, and ORD**.
2. Strengthen severe-weather contingency planning and proactive disruption management.
3. Prepare additional operational resources during high-delay months, particularly **July and December**.
4. Investigate carrier, NAS, and late-aircraft delays to reduce controllable operational disruptions.
5. Benchmark airline operational practices to identify potential improvement opportunities.
6. Improve weather monitoring, schedule buffers, contingency resources, and passenger communication during severe weather events.

## Business Impact

The dashboard supports:

- Identification of high-risk airports and operational hotspots.
- Seasonal and weather-driven disruption analysis.
- Identification of major delay causes.
- Data-driven operational planning.
- Resource allocation and disruption management.
- Monitoring of on-time performance.
- Better understanding of factors affecting passenger experience.

## Interactive Dashboard Features

The Power BI dashboard includes interactive filters for:

- **Airline**
- **Month**
- **Origin Airport**

These filters allow users to analyze flight delay performance across different operational segments.

## How to Use

1. Download the Power BI `.pbix` file from the `PowerBI` folder.
2. Open the file using Microsoft Power BI Desktop.
3. Use the dashboard filters to explore different airlines, months, and airports.
4. Interact with the visualizations to analyze flight delay patterns.

## Conclusion

The Flight Delay Operational Dashboard provides a consolidated view of flight performance and delay patterns across multiple operational dimensions.

The analysis highlights significant differences in delay rates across airports, airlines, states, months, and weather conditions. Weather-related disruption and high-delay operational locations represent important areas for further investigation and planning.

The project demonstrates how Power BI, Power Query, and DAX can be used to transform operational data into interactive dashboards and actionable business insights.

## Future Scope

- Develop predictive models for flight delay forecasting.
- Integrate real-time flight data for continuous monitoring.
- Build airport-level operational performance tracking.
- Analyze passenger-level impact of flight delays.
- Develop automated alerts for high-risk weather and operational conditions.

## Skills Demonstrated

**Power BI • Power Query • DAX • Data Cleaning • Data Transformation • Data Visualization • KPI Development • Exploratory Data Analysis • Business Intelligence • Business Insights • Operational Analytics**
