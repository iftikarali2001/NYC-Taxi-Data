# NYC Yellow Taxi Data Analysis 🚕📊

## Project Overview

This project analyses **NYC Yellow Taxi trip data** to understand travel patterns, revenue behaviour, surcharges, passenger trends, and tipping behaviour across **time and location**.

The goal of the analysis is to:

* Identify demand patterns across hours, days, and months
* Understand surcharge behaviour based on pickup and dropoff locations
* Study passenger count and tipping trends
* Provide simple, data-driven insights for routing, cab positioning, and pricing strategies

The analysis focuses on **exploratory data analysis (EDA)** with clear visualisations and practical interpretations.

---

## Dataset Used

The data used in this project comes from the **official NYC Taxi & Limousine Commission (TLC)**.

🔗 **Original Dataset Link:**
(https://www.nyc.gov/site/tlc/about/tlc-trip-record-data.page)

Specifically, this project uses **Yellow Taxi Trip Records**, which include information such as:

* Pickup and dropoff datetime
* Pickup and dropoff location IDs
* Trip distance and duration
* Fare, tips, surcharges, and total amount
* Passenger count

Taxi zone boundaries are taken from the official TLC taxi zone shapefile provided on the same website.

---

## Key Analyses Performed

* **Data Cleaning & Standardisation**

  * Handling invalid trip distances and durations
  * Fixing inconsistencies in fare-related fields
  * Standardising column names and data types

* **Time-based Analysis**

  * Trips and revenue across hours of the day
  * Weekday vs weekend traffic patterns
  * Monthly revenue trends

* **Location-based Analysis**

  * Pickup vs dropoff surcharge behaviour
  * Zone-level and borough-level comparisons
  * Geographic visualisation using taxi zone shapefiles

* **Passenger Behaviour**

  * Passenger count variation across time and zones
  * Group travel patterns on weekends and evenings

* **Tipping Analysis**

  * Tip percentage vs time of day
  * Tip percentage vs trip distance
  * Tip percentage vs passenger count

---

## Tools & Libraries Used

* Python
* pandas, numpy
* matplotlib, seaborn
* geopandas (for spatial analysis)

---

## Key Insights (High Level)

* Surcharges depend more on **where trips end** than where they start
* Manhattan and airport zones are consistently surcharge-heavy
* Daytime hours generate most trips and revenue
* Passenger count is higher during evenings and weekends
* Short trips tend to have higher tip percentages than long trips

---

## Repository Structure

```
├── data/              # shape files datasets
├── notebooks/         # Jupyter notebooks with full analysis
├── Images/            # Saved plots and visualisations
├── Report/            # Project documentation
```

---

## Notes

* The dataset is large, so sampling was used where required for efficiency.
* All analysis is based on cleaned data to ensure reliable insights.
* This project is intended for **learning and analytical demonstration purposes**.

---

## Acknowledgements

Data source:
NYC Taxi & Limousine Commission (TLC)
[https://www.nyc.gov/site/tlc/about/tlc-trip-record-data.page](https://www.nyc.gov/site/tlc/about/tlc-trip-record-data.page)

