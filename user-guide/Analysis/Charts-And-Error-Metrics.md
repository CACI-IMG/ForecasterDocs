# Charts and Error Metrics
Forecasts charts are available under the **Analysis** tab. These charts display both actual target values as well as the forecasts.The data can be viewed in two different chart types; a time series plot or a scatter plot, as below.


![Time Series Chart](imgs/Charts_TimeSeriesChart.png)


![Scatterplot](imgs/Charts_Scatterplot.png)


## Selecting Actual and Predicted values

| Group                                                                                                                                                                                | Description                                                                                                                                                                                                   |
|--------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------|---------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------|
| Select from Actuals                                                                                                                                                                  | Select the project or snapshot which contains the relevant actuals.  Only one project can be selected. This selection defines the x axis, the training and forecast start lines (orange and blue respectively), and the Actual (target column) values.                                                                                              |
| Select from Predicted                                                                                                                                                                | Any number of projects can be selected here. As the x axis of the chart is defined by the Actuals selection, data must cover a similar time range (and the same granularity, such as daily or interval). |

## Navigating the charts

- Clicking on the **Show Full Range** button flips between showing the forecast period (the default), and the entire dataset.
- The mouse wheel controls zooming in and out (horizontal zooming)
- Data can be panned by clicking on the chart and dragging
- Zoom into a specific area by holding down the Shift key and dragging with the mouse
- Ctrl + mouse wheel zooms vertically only
- Shift + mouse wheel zooms both horizontally and vertically


For the Time Series Chart, the legend contains error metrics for each forecast project or snapshot so that the user can assess the performance of each forecast when compared to the actuals.  The three error metrics are root mean square, mean absolute error and PE and are calculated for the validation set only.


## Error metrics

Error metrics for each Predicted series are shown in the chart legend below the plot. Error metrics show the accuracy of a forecast by summarising the different between actual values and a model's forecasts. Small values show that the error is small, meaning that forecasts and actuals are close. The error metrics shown on these charts are calculated over the **forecast range only** (on the chart, this is generally all the rows after the dotted blue line for which both actual and forecast values are available).

For the 2 error metrics described below (RMS, MAE), errors are measured in the same units as the forecasts, so an error of 30 on a daily call volume forecast means that the difference between actuals and forecasts is around 30 calls.


| Error Metric                                                                                        | Formula | Description                                                                   |
|-----------------------------------------------------------------------------------------------------|:---:|-------------------------------------------------------------------------------|
| **Root Mean Square (RMS)**                                                                              |   $$\sqrt{\frac{1}{n}  \sum_{i=1}^n(f_i-\alpha_i)^2}$$      | The square root of the average of the squared errors. This is similar to a 1 sigma credible interval, so we'd expect around 68% of calls to lie within this distance of the forecasts.                         |
| **Mean Absolute Error (MAE)**                                                                          |   $$ \frac{1}{n} \sum_{i=1}^n \left\lvert{f_i-\alpha_i}\right\rvert$$      | The average of the absolute error (i.e. the error with  the +/- sign removed) |


Where $$n:=$$ number of observations in the validation set,  $$f_i:=$$ forecasted value for observation $$i$$, $$\alpha_i:=$$ actual value for observation $$i$$.