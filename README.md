# Understanding Flight Delays

This repository contains a comprehensive **data analysis project** focused on uncovering patterns and operational inefficiencies in historical flight data.  
The objective is to analyze factors contributing to delays to help airlines optimize scheduling and improve the passenger experience.

---

## Project Overview

Flight delays present significant financial and logistical challenges for both airlines and passengers.  
This project analyzes a dataset of over **300,000 flights** to identify which carriers, airports, and timeframes are most susceptible to disruptions.

---

## Dataset Description

The analysis is based on two primary datasets:  

- **flights.csv:** Detailed flight information including scheduled and actual departure/arrival times, carrier codes, and origin/destination airports  
- **airlines.csv:** Mapping of carrier codes to full airline names  

---

## Key Analytics & Findings

### 1. Delay Patterns by Carrier
- **Best Performers:** Alaska Airlines Inc. and Hawaiian Airlines Inc. had the lowest average arrival delays  
- **Worst Performers:** Frontier Airlines Inc. and AirTran Airways Corporation had the highest average arrival delays  

### 2. Operational Efficiency: "Time Gained in Air"
- Metric **`time_gained_in_air`** measures an airline’s ability to recover time during the flight  
- **Top Recoveries:** Alaska Airlines Inc. and American Airlines Inc.  
- **Poor Recoveries:** Frontier Airlines Inc. and AirTran Airways Corporation lost more time during flights  

### 3. Route and Airport Analysis
- **Top Route:** JFK → LAX was the most frequently traveled path  
- **Airport Performance:** Aggregated average delays by origin airport to identify bottlenecks  

### 4. Temporal Trends
- Analyzed delays by **month** and **hour** to identify seasonal or daily peak disruption times  

---

## Tools & Libraries Used

- **Python** – Core programming language  
- **Pandas** – Data cleaning, merging, and feature engineering  
- **Data Visualization** – For uncovering patterns and trends  

---

## Conclusion

The insights generated from this analysis provide a **data-driven foundation** for airlines to improve on-time performance and enhance passenger satisfaction.  
This project highlights key carriers, routes, and times prone to delays, offering actionable intelligence for operational improvements.
