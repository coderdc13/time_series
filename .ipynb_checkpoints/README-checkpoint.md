# time_series
# Time Series Analysis


# General Introduction

This readme file is divided into three main sections, the time series analysis, the regression analysis, and the general conclusion. The time series analysis describes the main forecasting models: autoregressive moving average (ARMA), autoregressive integrated moving average (ARIMA), generalized autoregressive conditional heteroskedasticity (GARCH). For the regression analysis, the root mean squared error (RMSE) for a model was compared in terms of out-of-sample/test data and in-sample/trainer data. The general conclusion covers the conclusions from the points in this readme file.

## Time Series

The time series notebook focused mainly on ARMA, ARIMA, and GARCH modeling.

### ARMA

![student generated ARMA](images/ts/arma_student_blue.PNG)



In general, ARMA models work best on stationary data (http://www-stat.wharton.upenn.edu/~stine/insr260_2009/lectures/arma_forc.pdf). It could be stated that "the model does not fit the data" in this specific case. This is because the values in the P>|z| column of the ARMA Model Results are all much greater than .05. However, in the graph "Forecast for Five Day Returns," considering that one may consider the y axis as p values, this graph may be used to make the case that the model increases in predictive value over time.

### ARIMA


![student generated ARIMA](images/ts/ARIMA_student_blue.jpg)


One may consider ARIMA to be "the most general class of models for forecasting a time series" (https://people.duke.edu/~rnau/411arim.htm). Again, as for ARMA, for ARIMA, it could be stated that the model does not fit the data in this specific case. Just like for the ARMA Model Results, in the ARIMA Model Results, the values in the P>|z| column of the model are all much greater than .05. Still, 

### GARCH


![student-generated GARCH](images/ts/GARCH_student.PNG)


### Questions for Time Series Analysis

Based on your time series analysis, would you buy the yen now?

Is the risk of the yen expected to increase or decrease?

Based on the model evaluation, would you feel confident in using these models for trading?

## Time Series Discrepancies

### ARMA Discrepancies

![answer for ARMA](images/ts/arma_answer.PNG)

The image directly above is a snipped image from the starter code. In this directly image above, the the ARMA model results are given. The discrepancies in values between the starter code and the student-author's generated answers are provided below in light blue underline so as to make reading by the Instructor Grader easier.

![student generated ARMA](images/ts/arma_student_blue.PNG)


### ARIMA Discrepancies

![answer for ARIMA](images/ts/ARIMA_answer.PNG)

The image directly above is a snipped image from the starter code. In this directly image above, the the ARMA model results are given. The discrepancies in values between the starter code and the student-author's generated answers are provided below in light blue underline so as to make reading by the Instructor Grader easier.

![student generated ARIMA](images/ts/ARIMA_student_blue.jpg)


### GARCH Discrepancies

Besides the discrepancies in date of execution of test (underlined in blue), the student-author could find no other discrepancies between the starter code answer key and the student-author's generated answers.

![answer for GARCH](images/ts/GARCH_answer.PNG)

![student-generated GARCH](images/ts/GARCH_student.PNG)



## Regression


### Root Mean Squred Error (RMSE)


![student generated rmse](images/regr/student_rmse.PNG)


The homework readme file stated that "Out-of-sample data is data that the model hasn't seen before (Testing Data)." Also, the homework readme file stated that "In-sample data is data that the model was trained on (Training Data)." 

### Question for Regression Analysis

Does this model perform better or worse on out-of-sample data compared to in-sample data?

This regression model is exactly like the example that Instructor GS gave in class. Just like that class example, the root mean squared error of the out-of-sample was less than the root mean squared error of the in-sample. In this case, the in-sample RMSE is 0.5963660785073426. For the out-of-sample, the RMSE is 0.4154832784856737. The model may fit better with the data that the model hasn't seen before instead of the data on which the model was trained.

## Regression Discrepancies

There were at least two (2) discrepancies identified. One conflict was the difference in the X_train dataset between the starter code and the student-author generated version. The other conflict was the difference in the Root Mean Squared Error (RMSE) between the starter code and the student-author generated version.

### X Train Discrepancies

![answer for X_train dataset](images/regr/answer_X_train_1218_rows.PNG)

The image directly above is a snipped image from the starter code. In this image directly above, there are 1218 entries. This set conflicts somewhat with the student author's answer that is directly below in this section and pasted.

![student generated X_train dataset](images/regr/student_X_train_966_rows.PNG)


### Discrepancies for Root Mean Squared Error (RMSE)


![answer for rmse](images/regr/answer_rmse.PNG)

The image directly above is a snipped image from the starter code. The student author focuses on the two values for Out-of-Sample Root Mean Squared Error (RMSE) for In-Sample RMSE. These values conflict somewhat with the student author's answer that is directly below and pasted.

![student generated rmse](images/regr/student_rmse.PNG)

(Nota Bene: 99.99% of this work comes directly from class material, including and especially the starter notebooks, Instructor GS, Instructor KS, Instructor AN, and Tutor, Ms. LT!)