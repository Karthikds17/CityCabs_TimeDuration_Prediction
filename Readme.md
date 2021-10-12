Tried a variety of models to try and accurately predict the cab trip duration based off the features that are available.  

Attempted to use Linear Regression because it is an explanatory model, so would have been able to identify what features contributed to the cab trip duration. 
The linear regression model had a mean squared error of 114649.2 and a R2 value of .612, so it only explained 61.2% of the variation in the duration target variable. The mean average percent error for the linear regression model was 66.92%. The combination of these different factors indicate that the linear regression model is not a strong fit for predicting the cab trip duration. 

Next tried a decision tree because it is also another model that is useful for explaining which features contribute to the overall prediction of cab trip duration. 
However, the decision tree had a worse mean squared error of 121668.3 as well as a worse R2 value of .588. The mean average percent error was 56.24%. 
These indicate that the decision tree model is not a strong fit for predicting the cab trip duration. 

Although would like to use more explanatory models, the predictability of these models has not been able to generate the accuracy that is desired. 
Moved on to trying different models that could generate better predictions. XG Boost was the next model attempted. 
The mean squared error was 57045.5, so the values were nearly half of the previous models tried. The R2 value was .806, 
so the model was able to explain 80.6% of the variation in the duration target variable. 
Attempted to adjust some of the parameters for the XG Boost model, but the parameter tuning resulted in worse overall performance metrics. 
The XG Boost model has been our best model so far. 

Next tried the gradient boost model. 
The mean squared error was 76584.4 which was better than the linear regression and the decision tree model, but not as low as the XG boost model. 
The R2 value was .739, so the model was able to explain 73.9% of the variation in the duration target variable. 
The MAPE was 48.21% which was better than both the linear regression and decision tree model, but not as good as the XG Boost model.
The XG Boost model was still better overall. 

The last model tried was the random forest model. 
Although one decision tree did not produce strong results, hoped that the random forest would be able to. 
The random forest model had a MSE of 57092.7, R2 value of .806, and a MAPE of 44.67%. 
Overall, the random forest model was close to the XG Boost, but the XG Boost model still performed slightly better than the random forest model. 
The XG Boost model is the best model for determining cab trip duration. 

Conclusion 
After trying out multiple different models, was able to conclude that XG Boost best predicted the cab trip duration. 
Although XG Boost had relatively strong predictability, the model only explained 80.6% of the variation in the duration target variable. 
This indicates that there could be other data that could be added to better predict the cab trip duration. 
With additional data, the XG Boost model could improve further. 
