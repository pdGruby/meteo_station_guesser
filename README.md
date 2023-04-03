# What is it?
Logistic regression model for guessing synoptic stations based on the specific meteorological variables

# Summary
- Logistic regression works well for specific stations, especially when pretty unique stations are chosen
- Logistic regression have problems with recognition when there are stations with relatively similar climates - it is not surprising, a climatologist would also have problems with recognizing the stations properly on the basis of chosen variables
- To improve the model performance, we could use more data for each station and use more variables (i.e. precipitation, cloud cover, wind direction etc.). Changing the model hyperparameters should not improve the model performance by much - the problem here is the amount of provided data and the data's nature
