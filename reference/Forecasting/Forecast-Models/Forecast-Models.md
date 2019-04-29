
# All Forecasting Models

This sections gives details of all the Forecast Models (found in the Model Tab). These really are the core of Forecaster, and are the algorithms that produce the forecasts, based on learning from historical data and user overlays.
The first section to be added to the How To... section will cover the advantages and drawbacks of each of these models, as well as talking about the best places to use each of these.
For each data type (interval, daily, weekly, etc.), the top 3 models appear on individual buttons under the Model Design section of the Model tab. They can typically be run with default parameters, but the *Parameters* button provides details of the algorithm used, as well as information and control over all parameters. 

As a rule of thumb, it is always worth starting with simple seasonal models with few if any inputs, then moving to more advanced models that learning from inputs as appropriate. Those simple seasonal models are easy to interpret, are robust, and can work very well even when no business drivers are available. To get the absolute best forecasts, however, machines learning models such as Regression or Random Forests are recommended in order to learn as much as possible from business drivers (inputs). For daily to monthly data, the relevant *Multi Profile Model* is recommended as a first model, moving then to *Moving Average Regression* or *Random Forest* as needed.

Interval level models are in a separate section below, as these typically work in a different way from daily and above models (although machines learning models such as *Moving Average Regression* or *Random Forest* can sometimes be used to great benefit on interval data, in particular when many business inputs are available).

## Multi Profile Models

Those simple seasonal models are easy to interpret, are robust, and can work very well even when no business drivers are available. They can work surprisingly well, and are always worth trying as a first pass on a new problem, even if only to set a quick performance benchmark. For more powerful machine learning, and to infer the effects of business drivers (inputs), look instead to the *Moving Average Regression* or *Random Forest* models under the **Generic Models** section below.

- [**Multi Profile Daily**](Multi-Profile-Daily.md): 

- [**Multi Profile Weekly**](Multi-Profile-Weekly.md): 

- [**Multi Profile Monthly**](Multi-Profile-Monthly.md): 


## Generic Models
- [**ARIMA Auto**](ARIMA-Auto.md): ARIMA models are good at following trends, and can also learn from business drivers (inputs) when available. This *Auto* version searches for the optimal set of parameters. For more manual control, use *ARIMA-Manual* instead

- [**ARIMA Manual**](ARIMA-Manual.md): ARIMA models are good at following trends, and can also learn from business drivers (inputs) when available. This *Manual* version gives you the most control over individual model parameters. For more automation, use *ARIMA-Auto* instead.

- [**Exponential Smoothing Auto**](Exponential-Smoothing-Auto.md): 

- [**Exponential Smoothing Manual**](Exponential-Smoothing-Manual.md): 

- [**Forecast From Columns**](Forecast-From-Columns.md): 

- [**Formula Forecast**](Formula-Forecast.md): 

- [**Moving Average Regression**](Moving-Average-Regression.md): 

- [**Random Forest**](Random-Forest.md): 

- [**Regression Line**](Regression-Line.md): 

- [**STL Decomposition Auto**](STL-Decompositon-Auto.md): 

- [**Random Forest**](Random-Forest.md): 

- [**Weekly Profile**](Weekly-Profile.md): 


## Interval Models

- [**Weekly Interval Profile Principal Components**](Weekly-Interval-Profile-Principal-Components.md): 

- [**Weekly Interval Profile Smoothed**](Weekly-Interval-Profile-Smoothed.md): 

- [**Weekly Interval Profile**](Weekly-Interval-Profile.md): 






