# MLproject
ML project submission 
In the present project we try to predict the manner in with exercices are done
we Load training and testing datasets from project directory.the first dataset `pml-training.csv`contain 19622 observation of 160 variables. 
The second dataset `pml-testing.csv`contain 20 observation of 160 variables. Then we clean the sets by supressing columns with 
"NA".
we use cross validation an random forest to build predictive model. the model is used to predict classes of 20 observations
