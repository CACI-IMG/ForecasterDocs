
# *Regression Line* Forecast Model

This section covers how to use the *Regression Line* forecast model. This model simply fits a straight line to the data from the training range, and uses this to forecast.

Once *Regression Line* is selected from the drop-down at the top of the Script Selector dialog, you should see the parameters as shown below. You can very often run with the default parameters without needing to change anything else. The parameters and their effects are described here, but these details can also be found by hovering over the blue **(i)** icon in front of each parameter name.

![Regression Line](imgs/Model_RegressionLine.png) 

## *Regression Line* parameters

- **Overlay column - overwrite**: Non-missing values in this column are used to overwrite the model forecast
- **Overlay columns - multiply**: Non-missing values in these columns are used to multiply the model forecast (after any overwrite overlays)
- **Overlay columns - add**: Non-missing values in these columns are added to the model forecast (after any multiplicative overlays)
