## Datasets

We have split the `wildfires.csv` dataset into a training dataset (`wildfires_train.csv`) and test dataset (`wildfires_test.csv`). They are contained in the **data** subdirectory along with a codebook.   

### Exercise 1 
The total area burned by a wildfire is of great concern to government planners. This is captured by the variable `burned` in the `wildfires` dataset, which is a continuous variable. In this exercise, you will train models to predict `burned` using other variables in the data (**exclude `wlf` as a predictor** ). Train the following candidate models:

* boosting
* bagging
* random forests 
* linear regression
* ridge regression 

Be sure to properly tune all of these models, including any primary tuning parameters (e.g., `mtry`) or tuning parameters that appear relevant. 
Compare the estimated test errors for each model to determine which is best. 

<br><br>

### Exercise 2
Located in the northeast of the wilderness area is a wildlife protection zone. It is home to several rare and endangered species, and thus conservationists and park rangers are very interested in whether a given wildfire is likely to reach it. In the data, fires that reach the wildlife protection zone are denoted by the indicator variable `wlf`. 
In this exercise, you will train models to predict `wlf` using other variables in the data (**there is no exclusion on which varibles to use as predictors**). Train the following candidate models:

* boosting
* bagging 
* random forests
* logistic regression
* ridge logistic regression
     
Be sure to properly tune all of these models, including any primary tuning parameters (e.g., `mtry`) or tuning parameters that appear relevant. 
Compare the estimated test errors for each model to determine which is best. 
