# 🌦 Weather Data Schema

A structured overview of fields available in the weather dataset, grouped by context.

---

## 🌤️ Current Weather

- `last_updated_epoch`
- `last_updated`
- `temp_c`
- `temp_f`
- `is_day`
- `text`
- `icon`
- `code`
- `wind_mph`
- `wind_kph`
- `wind_degree`
- `wind_dir`
- `pressure_mb`
- `pressure_in`
- `precip_mm`
- `precip_in`
- `humidity`
- `cloud`
- `feelslike_c`
- `feelslike_f`
- `vis_km`
- `vis_miles`
- `gust_mph`
- `gust_kph`
- `uv`
- `windchill_c`
- `windchill_f`
- `heatindex_c`
- `heatindex_f`
- `dewpoint_c`
- `dewpoint_f`

---

## 📅 Forecast / Future / History

### 🔹 forecastDay
- `date`
- `date_epoch`

### 🔹 day
- `maxtemp_c`
- `maxtemp_f`
- `mintemp_c`
- `mintemp_f`
- `avgtemp_c`
- `avgtemp_f`
- `maxwind_mph`
- `maxwind_kph`
- `totalprecip_mm`
- `totalprecip_in`
- `avgvis_km`
- `avgvis_miles`
- `avghumidity`
- `text`
- `icon`
- `code`
- `daily_will_it_rain`
- `daily_will_it_snow`
- `daily_chance_of_rain`
- `daily_chance_of_snow`
- `uv`
- `totalsnow_cm`

---

## 🌞 Astro Data

- `sunrise`
- `sunset`
- `moonrise`
- `moonset`
- `moon_phase`
- `moon_illumination`
- `is_sun_up`
- `is_moon_up`

---

## ⏰ Hourly Forecast

- `time_epoch`
- `time`
- `temp_c`
- `temp_f`
- `is_day`
- `text`
- `icon`
- `code`
- `wind_mph`
- `wind_kph`
- `wind_degree`
- `wind_dir`
- `pressure_mb`
- `pressure_in`
- `precip_mm`
- `precip_in`
- `snow_cm`
- `humidity`
- `cloud`
- `feelslike_c`
- `feelslike_f`
- `windchill_c`
- `windchill_f`
- `heatindex_c`
- `heatindex_f`
- `dewpoint_c`
- `dewpoint_f`
- `will_it_rain`
- `will_it_snow`
- `vis_km`
- `vis_miles`
- `chance_of_rain`
- `chance_of_snow`
- `gust_mph`
- `gust_kph`
- `uv`
- `short_rad`
- `diff_rad`

---

## 🌊 Marine Weather

- `tides`
- `tide_time`
- `tide_height_mt`
- `tide_type`

---

## 🌊 Marine Hourly (Wave Forecast)

- `sig_ht_mt`
- `swell_ht_mt`
- `swell_ht_ft`
- `swell_dir`
- `swell_dir_16_point`
- `swell_period_secs`
- `water_temp_c`
- `water_temp_f`
