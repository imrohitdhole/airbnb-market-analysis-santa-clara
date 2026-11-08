# Airbnb Market Analysis — Santa Clara County

Exploratory and geospatial analysis of Airbnb listings in Santa Clara County, built to understand pricing, availability, reviews, host concentration and where listings cluster across the county.

> Group project (five people) for a graduate data visualization course at San José State University.

## Demo

🎥 YouTube walkthrough: https://youtu.be/4LTOOuzI07E

[![Project Demo](https://img.youtube.com/vi/4LTOOuzI07E/0.jpg)](https://youtu.be/4LTOOuzI07E)

## What's inside

| File | Contents |
|---|---|
| `Airbnb.ipynb` | Data cleaning, exploratory analysis and the five dashboards below (Google Colab notebook) |
| `report/Group6_DV_ProjectReport.pdf` | Full project report with findings, visuals and recommendations for hosts and travelers |

## Analysis

The notebook cleans the listings data (handling missing values such as `reviews_per_month`), then builds five dashboard-style sections:

1. **Price analysis:** price distribution and average price by room type.
2. **Occupancy and availability:** availability distribution and occupancy by room type.
3. **Reviews and ratings:** neighborhoods and listings with the most reviews.
4. **Host analysis:** hosts with the most listings.
5. **Geographic distribution:** an interactive Folium map of listings across the county.

## Tech

Python · pandas · Matplotlib · Seaborn · Folium · Google Colab

## How to run

1. Download the Santa Clara County `listings.csv`, `reviews.csv` and `neighbourhoods.csv` files. They aren't included in this repo.
2. Open `Airbnb.ipynb` in Google Colab (or Jupyter) and put the three CSVs in the notebook's working directory; in Colab, upload them to `/content`. The first cell mounts Google Drive, which you can skip when running locally.
3. Run the notebook top to bottom.
