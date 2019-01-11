# Model Design

A number of forecasting methods are available in the CACI Forecaster.


### The Three Core Forecasting Methods
The CACI Forecaster offers three core forecasting models, each requiring input columns which are incorporated into the forecast as additional drivers. In order to allow for multiplicative data, the application provides you with the option to take the natural logarithm of the target variable prior to forecasting.  This is available in the Settings icon once you have selected the relevant forecasting method.


| Method          | Description                                                                                                                                                                                                                                                  | Input Columns                                                                                                                                        |
|-----------------|--------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------|------------------------------------------------------------------------------------------------------------------------------------------------------|
| Simple Profile  | Creates a daily level multi profile model, based on day of week, week of month and month of year profiles.                                   | Automatically selects the most relevant input columns                                                                                                |
| Regression      | Using a stepwise approach, the application generates an equation to calculate the target variable using a linear combination of the most relevant inputs.  A multiplicative model is also possible by taking the natural logarithm of the target variable.   | Automatically selects the most relevant input columns                                                                                                |
| Random Forests  | Based on Decision Trees, Random Forests is a flexible and powerful machine learning algorithm that produces a great result most of the time.                                   | Automatically selects the most relevant input columns                                                                                                |



The general approach is to create all the forecasts with a simple but robust model such as the Simple Profile. That will get robust ballpark forecasts very quickly. For most of the smaller volume lines, that's probably the best approach. For higher volume or higher value lines, analysts can then go in and work on adding drivers using more advanced models such as Regression and Random Forests. 


<!-- When including inputs, it is usually best to start with the regression model as it will select the most appropriate inputs and provide you with a visible formula (therefore giving insight into the problem).  Once you have generated a regression model, you may find that a decision tree model shows better performance.  After filtering out any irrelevant inputs, neural networks can be used for maximum performance. -->


### Custom Models
In addition to the three core methods described above, CACI Forecaster offers a number of custom models that focus more on time series methods such as ARIMA and Exponential Smoothing.  

<!-- Table 10 provides a description of each model and its general performance with different types of data.  More details can be found in a separate document on custom models [2].
It is worth mentioning that, apart from the ARIMA models, any input columns will be ignored. -->

Bespoke forecasting models can be created by CACI if required. For more details on additional consultancy, contact CACI.
