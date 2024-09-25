# Can Wholesale Electricity Prices Be Predicted Using A SARIMA Model?

See the blog post at: https://medium.com/@jake.wernham/can-wholesale-electricity-prices-be-predicted-using-a-sarima-model-5e067c5be4d0

## Motivation

This project was motivated by the ever increasing need for utilities, traders and policymakers to forecast wholesale electricity prices accurately despite increasing market volatility. Specifically, I wanted to provide a model which would answer the below question with a reasonable level of certainty.

*What will the wholesale price of electricity be for next month?*

## Setting Up The Solution

### Libraries Used

A list of the libraries used in my work is as follows:

- pandas
- numpy
- datetime
- dateutil
- statsmodels
- sklearn
- math
- tabulate
- matplotlib

### The Files

- NLMonthlyDA.csv : a csv file containing monthly average wholesale electricity prices in The Netherlands, dating back to January 2015.
- ARIMADA.ipynb : a Jupyter Notebook containing all of the analysis used to answer the main problem question.

### The Results

The result of this investigation into answering the key initial question was that a SARIMA model can indeed be used, with a reasonable level of accuracy, to predict the wholesale electricity price for the next month. However, a model which also accounts for exogenous factors, such as load, would potentially provide an improved model.

### Acknowledgements

I would like to acknowledge the following sources which I read and found useful in answering this question.

* https://medium.com/r/?url=https%3A%2F%2Fwww.energy-charts.info%2Fcharts%2Fprice_average%2Fchart.htm%3Fl%3Den%26c%3DNL
* https://medium.com/r/?url=https%3A%2F%2Fwww.kaggle.com%2Fcode%2Fiamleonie%2Ftime-series-interpreting-acf-and-pacf
* https://medium.com/@nikhilmalkari18/seasonal-decomposition-425a2d7490e8
* https://www.statisticshowto.com/adf-augmented-dickey-fuller-test/
