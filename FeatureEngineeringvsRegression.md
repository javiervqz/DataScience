What I hope to achive with my notebook, is to show why knowing your data, and what you'd like to achieve is exponentially better than the most complex of models you can build.
T​he most complex model that I built with the sample dataset, was a multiple regression model using "FUELTYPE" as a categorical variable and 3 other variables. The best result I was able to achieve was:
Mean absolute error: 14.13
Variance score: 0.91
Residual sum of squares (MSE): 380.01
But is this good? Does it solve the problem? 
If the problem is "How can we reduce emissions?" Then No.  Because the combined fuel consumption is the best predictor if you take into account the fuel being used. And with this complex model, we just sparsed out focus to three expensive variables to control
With 3 Simple regression models, we can just pass the recommendation to change the fuel type. Then come back to the drawing board  when more data in the better fuel is colected. 
So the next step in our analysis is then, how to reduce consumption? With Fuel Type E (It seems to consume more fuel, so emissions should drop, once consuption is controlled)
The average MSE for these three models is 0.09 and R^2 = 1




