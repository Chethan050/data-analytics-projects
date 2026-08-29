# Automobile Sales Analysis Dashboard

Analysis of historical automobile sales data to understand how sales patterns change during economic recessions, using static visualizations and an interactive dashboard.

## Project Structure

- `automobile_sales_visualizations.ipynb` — Static visualizations (Matplotlib, Seaborn, Folium): sales trends by year, advertising spend vs. sales, sales by vehicle type, GDP comparison during recession vs. non-recession, seasonality effects, consumer confidence, and a map of sales by office location.
- `automobile_sales_dashboard.py` — Interactive dashboard built with Plotly Dash. Lets the user choose "Yearly Statistics" or "Recession Period Statistics" and a year, then renders the relevant charts (sales trend, sales by vehicle type, advertising expenditure share, and effect of unemployment rate on sales).

## Key Questions Explored

- How do automobile sales fluctuate year to year, and how do they behave specifically during recession periods?
- How does advertising expenditure track with sales during non-recession periods?
- Which vehicle types are most/least affected by recessions?
- How does GDP move differently during recession vs. non-recession periods?
- What effect does unemployment rate have on sales by vehicle type?

## Tech Stack

- Python, Pandas, NumPy
- Matplotlib, Seaborn, Folium (static visualizations)
- Plotly, Dash (interactive dashboard)

## Running the Dashboard

```bash
pip install dash pandas plotly
python automobile_sales_dashboard.py
```

Then open the local address shown in the terminal (usually `http://127.0.0.1:8050`).

## Data Source

Automobile sales dataset (1980–2023) provided as part of the IBM Data Visualization with Python course.
