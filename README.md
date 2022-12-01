# Lithium-Battery-Capacitance

### Introduction 
Lithium-ion battery has been widely used in electric devices for its high energy density and excellent low temperature performance. 
The main challenge of Lithium-ion battery is its performance degradation and remaining useful life estimation. 
As a results, this final project focuses on lithium-ion battery remaining useful life estimation and prediction with NASA battery data set. 
Lithium-ion batteries were run through 3 different operational profiles(charge, discharge, and electrochemical impedance spectroscopy). 
In the NASA data set, the measured volage and current, the charged voltage and current in both charging and discharging cycle at different temperature are provided by the Prognostics CoE at NASA Ames.
#### Dataset origin:
Prognostics Data Repository is a collection of datasets that have been donated by agents. 
This battery data set is provided by NASA Ames and collected from the experiment on Li-thium Battery Prognostics PCoE 
Dataset: https://ti.arc.nasa.gov/tech/dash/groups/pcoe/prognostic-data-repository/
#### Proposed Plan
We plan on using one of the models practiced during the course or exponential/logarithmic fitting. 
We will start by calculating the regression metrics for the models;
Linear Regression
Ploynomial Regression
Exponential/logarithmic Regression
Neural Network
The purpose of plotting the regression metrics values is to identify the best fitting for the battery's capacity data.
Once we identify the best fit, the next step will be to fit the model onto one of the battery's data, and use that to estimate the Rest Useful Life for the other batteries.
