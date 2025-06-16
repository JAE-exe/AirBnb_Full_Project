# 🏡 Airbnb Price Analysis – Tableau Project

This Tableau project analyzes Airbnb listing data to uncover patterns in pricing, availability, and revenue potential across different zip codes and bedroom counts.

---

## 📊 Dashboard Overview

The interactive dashboard provides insights through multiple visualizations:

* **Average Price Per Bedroom**
  Shows how listing prices vary with the number of bedrooms.

* **Bedroom Listing Counts**
  Displays the count of distinct listings by bedroom count.

* **Price Per Zipcode (Map View)**
  Geographic map of average prices by zipcode for regional comparison.

* **Price By Zipcode (Bar Chart)**
  Ranks zipcodes based on average price for clearer insights.

* **Revenue Per Year**
  Time-series analysis of cumulative revenue (calendar price) across 2016.

---

## 🛠 Features Used in Tableau

The following Tableau capabilities were applied in building this analysis:

| Feature               | Usage                                                                                  |
| --------------------- | -------------------------------------------------------------------------------------- |
| **Calculated Fields** | Created custom metrics like average price and total revenue.                           |
| **Bins**              | Grouped continuous values (e.g., price) to simplify visualizations.                    |
| **Joins**             | Merged multiple data sources (e.g., calendar, listings, zipcode) for unified analysis. |
| **Map Visualization** | Used geographical fields (zipcode) to create an interactive price heatmap.             |
| **Bar & Line Charts** | Compared average prices and tracked revenue trends over time.                          |
| **Color Encoding**    | Visualized price intensities by bedroom and region.                                    |
| **Filters**           | Enabled dynamic analysis of specific subsets like zipcodes or bedroom categories.      |

---

## 🧠 Key Insights

* **Price increases** with bedroom count — 6-bedroom listings average nearly \$585 per night.
* **Zipcodes like 98134 and 98119** tend to have the highest average prices.
* The number of **1-bedroom listings is dominant**, but larger listings generate more revenue per night.
* **Revenue steadily increased** throughout 2016 with some seasonal fluctuations.

---

## 📁 Included Files

| File                       | Description                                            |
| -------------------------- | ------------------------------------------------------ |
| `Airbnb_Dashboard.twbx`    | Tableau workbook with full dashboard and data sources. |
| `Dashboard_Screenshot.png` | Image preview of the dashboard.                        |
| `AirBnB_Dataset.xlsx` | The dataset used in the project                        |


---

## ✅ Tools Used

* **Tableau Desktop**
* **Mapbox Integration (for maps)**
* **Airbnb Open Dataset (Calendar & Listings)**


