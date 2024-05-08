# Yulu - Case Study

Understand the factors affecting the demand for these shared electric cycles in the Indian market using hypothesis testing.

Colab Notebook: [Yulu - Case Study](https://colab.research.google.com/drive/1ChVHFS-hk8AgYl_08uHRcONGaOajsRtf?usp=sharing)

## Overview of Yulu

Yulu stands as India's foremost micro-mobility service provider, offering distinctive vehicles tailored for daily commutes. Initially conceived to combat traffic congestion in India, Yulu presents the safest commuting solution through a user-friendly mobile application, facilitating shared, solo, and sustainable commuting.

Strategically positioned Yulu zones span various locations including metro stations, bus stands, office spaces, residential areas, and corporate offices, ensuring seamless, economical, and convenient first and last-mile connectivity.

Recently, Yulu has encountered significant declines in its revenues. In response, they've engaged a consulting firm to dissect the factors influencing demand for shared electric cycles within the Indian market.

## Problem Statement

This project endeavors to dissect the factors underpinning the demand for shared electric cycles in the Indian market. Specifically, the objective is to pinpoint the significant variables predictive of demand for these cycles and assess how effectively these variables elucidate electric cycle demand.

## Dataset

The dataset utilized for this analysis contains pertinent information regarding bike rentals and encompasses factors such as temperature, humidity, weather conditions, user types, and counts of bike rentals.

### Column Profiling

1. `datetime`: Date and time stamp.
2. `season`:

   - `1`: Spring
   - `2`: Summer
   - `3`: Fall
   - `4`: Winter

3. `holiday`: Indicates whether the day is a holiday or not, derived from the DC Government Holiday Schedule.

4. `workingday`: Binary indicator (1 for workdays, 0 for weekends/holidays).

5. `weather`:

   - `1`: Clear, few clouds, partly cloudy, or partly cloudy.
   - `2`: Mist, cloudy, broken clouds, or mist.
   - `3`: Light snow, light rain with thunderstorms and scattered clouds, or light rain with scattered clouds.
   - `4`: Heavy rain with ice pellets and thunderstorms, mist with heavy rain, or snow with fog.

6. `temp`: Temperature in Celsius.

7. `atemp`: "Feels like" temperature in Celsius.

8. `humidity`: Humidity level.

9. `windspeed`: Wind speed.

10. `casual`: Count of casual users.

11. `registered`: Count of registered users.

12. `count`: Total count of rental bikes, including both casual and registered users.

You can access the dataset [here](https://d2beiqkhq929f0.cloudfront.net/public_assets/assets/000/001/428/original/bike_sharing.csv?1642089089).
