# Dashboard-Global-Pharmaceutical-Spending (1970-2014)

### This Excel dashboard visualizes pharmaceutical drug spending data by country and decade, using data from the OECD and DataHub. Built with Power Query, Pivot Tables, and Slicers to enable dynamic exploration of trends across countries and time periods.  
---

## Features

- Interactive line chart: Total pharmaceutical spending over time
![LineChartGif](https://github.com/user-attachments/assets/6a278cb5-d5e0-4c34-aa40-fb720722ec5c)


- Bar chart by decade: Top 10 countries by per capita drug expenditure
![BarChartGif](https://github.com/user-attachments/assets/a842714a-c3db-4dd6-b9eb-8c1ea061748a)


- KPI cards: Highlighting top and bottom countries per decade  
![Top](https://github.com/user-attachments/assets/7c3c2849-84ba-4a8c-a255-ada1e3826a3a)
![Bottom](https://github.com/user-attachments/assets/c3d9a99f-27d7-4bb2-8e20-8311456785b6)

- World map: Color-coded by % of health expenditure on pharmaceuticals
![MapChart](https://github.com/user-attachments/assets/63364157-80a1-4de1-9307-96ebda2b0e18)

## Insights

This dashboard allows users to answer key questions such as:  
- Which countries have the highest or lowest pharmaceutical spending per capita?  
- How has drug spending evolved over time, and how does it vary by region?
These insights can be explored directly through the interactive visuals, including KPI cards, bar charts, trend lines, and a global map.  
> 🔒 The Excel sheet is initially protected to avoid accidental edits, but it can be unlocked if needed to manipulate or extend the dataset manually.

## Note

As shown in the line chart GIF, some countries lack complete data for the entire 1970–2014 period. Consequently, they may not appear in certain charts or decade-based rankings.
 
⚠️ In a future version of this project, we plan to address these data gaps by using linear regression models in Python to estimate missing values and reconstruct a more consistent time series for all countries.  
⬇️ You can download the dataset from [here](https://www.kaggle.com/datasets/tunguz/pharmaceutical-drug-spending-by-countries)
