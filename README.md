## COLUMN DESCRIPTION
**1. Date**: The date of observation. Format YYYY-MM-DD.

**2. Location**: The common name of the location of the weather station.

**3. MinTemp**: The minimum temperature recorded in degrees Celsius.

**4. MaxTemp**: The maximum temperature recorded in degrees Celsius.

**5. Rainfall**: The amount of rainfall recorded for the day in millimeters.

**6. Evaporation**: The Class A pan evaporation in millimeters in the 24 hours to 9 AM.

**7. Sunshine**: The number of hours of bright sunshine during the day.

**8. WindGustDir**: The direction of the strongest wind gust in the 24 hours to midnight.

**9. WindGustSpeed**: The speed of the strongest wind gust in kilometers per hour in the 24 hours to midnight.

**10. WindDir9am**: The direction of the wind at 9 AM.

**11. WindDir3pm**: The direction of the wind at 3 PM.

**12. WindSpeed9am**: Wind speed averaged over 10 minutes prior to 9 AM in kilometers per hour.

**13. WindSpeed3pm**: Wind speed averaged over 10 minutes prior to 3 PM in kilometers per hour.

**14. Humidity9am**: Humidity percentage at 9 AM.

**15. Humidity3pm**: Humidity percentage at 3 PM.

**16. Pressure9am**: Atmospheric pressure reduced to mean sea level at 9 AM in hectopascals (hPa).

**17. Pressure3pm**: Atmospheric pressure reduced to mean sea level at 3 PM in hectopascals (hPa).

**18. Cloud9am**: Fraction of the sky obscured by cloud at 9 AM, measured in oktas (eighths). A value of 0 indicates a completely clear sky, while a value of 8 indicates completely overcast conditions.

**19. Cloud3pm**: Fraction of the sky obscured by cloud at 3 PM, measured in oktas (eighths). See Cloud9am for a description of the values.

**20. Temp9am**: Temperature at 9 AM in degrees Celsius.

**21. Temp3pm**: Temperature at 3 PM in degrees Celsius.

**22. RainToday**: Boolean indicator (1 if precipitation in the 24 hours to 9 AM exceeds 1 mm, otherwise 0).

**23. RainTomorrow**: The amount of rainfall the next day in millimeters. Used to create the response variable RainTomorrow, indicating the "risk" of rain.