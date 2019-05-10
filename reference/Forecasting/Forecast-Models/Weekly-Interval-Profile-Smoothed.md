
# *Weekly Interval Profile Smoothed* Forecast Model

This section covers how to use the *ARIMA Auto* forecast model. ARIMA models are good at following trends, and can also learn from business drivers (inputs) when available.

Once *ARIMA Auto* is selected from the drop-down at the top of the Script Selector dialog, you should see the parameters as shown below. You can very often run with the default parameters without needing to change anything else. The parameters and their effects are described here, but these details can also be found by hovering over the blue **(i)** icon in front of each parameter name.

![ARIMA Auto](imgs/ScriptImporter_LoadWithHarmonicsDaily.png) 

## *Load With Harmonics - Daily* parameters


- **Correct for public holidays**: If selected, public holidays are removed from the ARIMA training data, 
and a public holiday scaling factor is then determined 
after the initial ARIMA forecast is produced
- **Public holidays column**: If left blank, defaults to one of IsHoliday, HolidaysInWeek, or HolidaysInMonth depending on date type
- **Seasonality (for non date key only)**: Only required or used if the key column is not a date. If the key column is a date, weekly or yearly seasonality is assumed. If no seasonality is present, leave blank or set to 1
- **Overlay column - overwrite**: Non-missing values in this column are used to overwrite the model forecast
- **Overlay columns - multiply**: Non-missing values in these columns are used to multiply the model forecast (after any overwrite overlays)
- **Overlay columns - add**: Non-missing values in these columns are added to the model forecast (after any multiplicative overlays)