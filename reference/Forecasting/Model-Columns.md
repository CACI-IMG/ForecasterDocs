# Model Columns
This part of the Model ribbon lets you select the column to be forecast, as well as any inputs the model might use.


### Column Types
Columns can be flagged up in two ways: 
-	**Input**:  Column is allowed as an input to the forecast model (provided the model in question uses inputs). For some models, all input columns will be used, however, for more powerful models such as *Moving Average Regression* or *Random Forest*, the models themselves will learn which of these permitted inputs are relevant, and will usually just chose a subset of these input columns.
-	**Target**:  Column to be forecast (only one can be selected)

To assign a column to a given column type, select the column name or range of columns. (Multiple columns can be selected using the `shift` key.) The selected columns will turn light blue as selected.  At this point you can select one of the column types: Input or Target.  
Once complete, the column background colour will change to reflect the colours of the column type: inputs are yellow whilst the target column is green.  The data grid should then appear similar to that shown in Figure 35.
 

![Target and Inputs in the Data Grid](imgs/ModelColumns_TargetInput.png)


### Excluding Columns
To exclude any data columns from any specific model (either as input or target), select the columns and then press the **Exclude Columns** button. This will not delete the columns, but will remove them from the model. The background colour of these columns will be returned to white.
To delete columns completely, you can instead use the **Delete Column** button on the *Data* tab.
