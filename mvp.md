# MVP

The goal for my regression project is to answer my hypothesis of is it possible to determine the prices for used car when knowing historical data.

I've so far got my data ready and turn them into numerical data. However, the categorical data has not yet fully develope into dummies variable, but for simple testing and finding relationships between the features, I used labeling technique to determine the categorical features to become numerical. Here is an overview of the pairplot:

![Pairplot_simple](https://user-images.githubusercontent.com/43353401/135163182-293072a2-c422-4ed8-8deb-c2301d8738dc.png)

As you can see, there are some relationship between the cost with the year, mileage, services.

By just taking this to apply the linear regression model without modifying or adding dummies features, I was able to get a R^2 score of 0.3568. So here is a chart of the model predicting the cost values.

![Jointplot_simple](https://user-images.githubusercontent.com/43353401/135163877-bc38928a-2191-4777-8cde-e9b5de558707.png)

As you can see, using the linear regression models, it will leads to high bias!
Here are the coeficients by ['Year','Mileage','Owners','Services','Brandl','Bodyl','Accl','Modell']
[ 1418.9906, -0.1187, -1002.3048, 142.3328, -176.4892, -3162.6663, 342.2964, -11.6402]
