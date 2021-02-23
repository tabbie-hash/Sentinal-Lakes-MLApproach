# Sentinal-Lakes-MLApproach
## Abstract:
The overall goal of this project is to explore unsupervised learning methods detecting climate change by looking for increased variability in temperatures. 
The Trout lakes dataset used is indeed novel but required sufficient pre-processing. Some dates had data missing some hours of the day. We oriented the data 
in a way that each row represented a date from respective months and each column represented respective years with the cells consisting of average temperature 
for the day. For statistical analysis we chose to look into the variance in the average temperature of the water for different dates across the years. 
For visualization we chose regression plots and faceted boxplots. Our baseline model was Lasso Regression Model and the model of our choice was GradientBoost Regressor model.

## Conclusion:
Overall, our findings showed that our hypothesis was supported. Additionally, many of our models performed well in training and testing scores but it was the mean 
squared errors that help differentiate each model from each other. If we worked on this project further, we would have liked to create predictive models to predict 
temperature’s variance by utilising covariance/standard error rather than average temperatures. Additionally, it would have been fruitful to explore other algorithms 
as the research suggests that there might be other algorithms that handle time series and hydrology relationships better. 
