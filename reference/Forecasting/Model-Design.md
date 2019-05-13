# Model Design

The *Model Design* section of the model tab lets you select and control the forecast model used for creating the forecast. Forecast models really are the core of Forecaster, and are the algorithms that produce the forecasts by learning from historical data and applying user overlays. 

A wide range of forecasting methods are available in Forecaster, however the most useful models for your specific data are always highlighted in the ribbon. For each data type (interval, daily, weekly, etc.), the top 3 models appear on individual buttons under the Model Design section of the Model tab. They can typically be run with default parameters, but the *Parameters* button provides details of the algorithm used, as well as information and control over all parameters. The recommended best 3 models for your data have their own buttons on the ribbon, while the full range of models is available from the *Other Models* button. Although all models should work well with default parameters, the *Parameters* button lets you change any of the parameters as needed, while also providing more information on each of the models.

This section provides an overview of the *Model Design* ribbon section operation. For in depth information on each of the forecasting models, see the [**All Forecast Models**](Forecast-Models/Forecast-Models.md) section.

## Models for Daily, Weekly, and Monthly Data
For daily data or above it is generally worth starting with simple seasonal models with few if any inputs (*Multi Profile* models), then moving to more advanced models that learn from inputs as appropriate (*Moving Average Regression* and *Random Forest* models). This approach is mirrored in the ribbon section, with the *Multi Profile* model selected by default, and the other recommended models assigned their own buttons:
![Daily, Weekly, Monthly Ribbon Models](Forecast-Models/imgs/Ribbon_Models.png) 


## Models for Interval Data
Forecaster provides a range of models specifically designed for use on interval level data. For interval level projects, the ribbon highlights these models instead. These models are generally based purely on seasonality, without using additional business drivers. Other models such as Regression or Random Forest can also be used on interval data. Although those other kinds of models are used less frequently on interval data, they can be extremely useful when business drivers are present.

![Interval Ribbon Models](Forecast-Models/imgs/Ribbon_ModelsInterval.png) 


 For in depth information on each of the forecasting models, see the next section on [**All Forecast Models**](Forecast-Models/Forecast-Models.md).


