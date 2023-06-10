### M11_CHALLENGE

# MERCADOLIBRE GROWTH ANALYSIS & FORECAST

In this Challenge, I have been tasked with using the power of time series implementation to mine, analyze, and forecast the financial and user data for the Latin American e-commerce giant, MercadoLibre. This project will accomplish the following:

1. Provide MercadoLibre with metrics of interest by  mining and analyzing data and creating visual depictions of seaonality within the Google search traffic.

2. Evaluate how the company's stock price correlates with its Google search traffic.

3. Use Prophet by Meta to create forecast models that will predict hourly user search traffic.

4. Plot a forecast for the company's future revenue. 

In a market that is growing at an exponential rate, even the powerhouses need to use innovative, cutting edge methods to streamline their business. Search results lead to revenue, and analyzing this metric is a critical part of any e-commerce business. In order to create streams of revenue, a business must understand its customers. That's where this program has the opportunity to put MercadoLibre above the rest, using the power of Prophet by Meta in tandem with Google Colab, this expansive program will provide MercadoLibre with invaluable data analysis and forecasts. 

## TECHNOLOGIES

In order for this immersive application to run, there are installation requirements. They are the following:

[Python](https://www.python.org/downloads/) - Enables the user to use the powerful Python programming language.

[JupyterLab](https://jupyter.org/) - Access to the web-based IDE JupyterLab.  

[Google Colab](https://colab.research.google.com) - An excellent tool for machine learning and data analysis, Google Colab allows users to write and execute python code wihtin a web browser.

[Prophet](https://facebook.github.io/prophet/docs/installation.html) - Allows users to forecast time series data trends using daily, weekly, and yearly seasonality as well as holiday periods based on additive models.

[Pandas](https://pandas.pydata.org/) - Grants access to the open-source Pandas data analysis tool, which is powered by Python.

[Microsoft Excel](https://www.microsoft.com/en-us/microsoft-365/excel) - Enables the user to read the compiled MercadoLibre Google Search, Daily Revenue, and Stock Price data.

## USAGE

In order to execute, plot, and simulate this code, you must run the following installs and imports in Google Colab:

INSTALLS (MUST BE RUN IN EVERY INSTANCE):

```
!pip install pystan
!pip install prophet
!pip install hvplot
!pip install holoviews
```
IMPORTS (MUST BE RUN IN EVERY INSTANCE):

```
forecasting_net_prophet.ipynb
import pandas as pd
import holoviews as hv
from prophet import Prophet
import hvplot.pandas
import datetime as dt
%matplotlib inline
from pathlib import Path
import numpy as np
```

## GALLERY

![image](https://github.com/MLeGare29/M11_CHALLENGE/assets/127421460/51b1edc3-decd-445f-a625-3028cd36a313)

![image](https://github.com/MLeGare29/M11_CHALLENGE/assets/127421460/4c8f832c-0528-41c7-a8c7-0aae03669378)

![image](https://github.com/MLeGare29/M11_CHALLENGE/assets/127421460/a0160780-1d4a-442b-ad03-592faadc34eb)

![image](https://github.com/MLeGare29/M11_CHALLENGE/assets/127421460/fd7e9d72-415a-45b3-8b1e-61eb8e1968f5)

![image](https://github.com/MLeGare29/M11_CHALLENGE/assets/127421460/0a0323f4-97e2-4ca9-9096-3e6bc79e9ffa)


### CONTRIBUTORS

*Marcus LeGAre (Author, Developer)*

*Deborah Aina (Learning Assistant)*

*Richie Garafola (Learning Assistant)*

*Roberto Salaza (Learning Assistant)*

### LICENSE

**COLUMBIA UNIVERISTY FINTECH BOOTCAMP**
