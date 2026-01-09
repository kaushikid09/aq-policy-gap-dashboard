# Processed datasets

These files are derived from raw OpenAQ CPCB station data.

## delhi_pm25_daily_nov2025.csv
Daily Delhi-level PM2.5 calculated by averaging across four CPCB reference monitors:
- Aya Nagar
- Anand Lok
- Greater Kailash
- Sector 5 Vasundhara

Aggregation:
- Hourly → daily
- mean_pm25 = mean across all readings
- median_pm25 = median across all readings
- stations_reporting = number of stations contributing data that day

These files are used for policy analysis and dashboard visualisation.
