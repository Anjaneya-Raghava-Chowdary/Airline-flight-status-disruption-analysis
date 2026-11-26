# Airline Flight Status & Disruption Analysis

An interactive Power BI practice dashboard exploring airline status records, monthly trends, cancellations by country, and simulated disruption reasons.

![Dashboard overview](images/dashboard-overview.png)

## Dashboard features

- KPI cards for total records, on-time rate, on-time records, delayed records, and cancelled records
- Monthly trends by flight status
- Flight-status distribution donut chart
- Cancelled-record counts by country
- World map grouped by continent
- Slicers for departure date, continent, country, flight status, and gender
- Reset button for returning to the default filter state

## Tools and techniques

- Power BI Desktop
- Power Query for date preparation
- DAX measures for report metrics
- Bookmarks for the reset interaction

## Data notes

The source data is at passenger-record level and does not include actual flight IDs or recorded disruption causes. The flight IDs and disruption-reason categories added for this practice project are simulated. They should not be treated as actual flight totals or airline-reported causes.

## Project files

- `report/Airline_Flight_Status_Disruption_Analysis.pbix` — Power BI report
- `images/dashboard-overview.png` — dashboard screenshot
