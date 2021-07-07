# COVID-19 forecast

This is an example of a Jupyter Notebook which forecasts when the critical value of 50 infections (7 days) per 100.000 inhabitants will be reached for all EU-countries

Comes with a docker-container to run the notebook in, if you are not willing to let it run in a [Google colab workspace](https://colab.research.google.com/github/joov/covid-forecast/blob/main/notebooks/covid-forecast.ipynb#) or on your own PC.

Rough idea:
- get 7-day infection rates for each country
- fit exponential function in a window of three values
- estimate duration to value of 50 from fit

Further explanations in contained in notebook.
