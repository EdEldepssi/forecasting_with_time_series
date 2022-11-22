## Problem Statement:

Human activities are changing Earth's natural greenhouse effect. Burning fossil fuels like coal and oil puts more carbon dioxide into our atmosphere.
Too much of these greenhouse gases can cause Earth's atmosphere to trap more and more heat. This causes Earth to warm up.

Using the BERKELEY EARTH dataset, Can we confirm that global warming exists?
How does average temperature changes in each season?
What are the top countries mostly to be affected by global warming over the next decade?
Forecast the average land temperature in the us over the next 10 years.

### Who would be interested in this project?
Govornment organizations who are concerned with global warming.


### Models used:
	- Baseline Model: Simple Moving Average, Exponentially Weighted Moving Average
	- ARIMA Model

### Metrics of Success:
	- Root mean squared error

### tsa_eda.ipynb:
	Time Series Analysis and Exploratory Data Analysis

### modeling.ipynb
	Building a baseline model, predicting on testing data and forecasting for 10 years in the future.

### Datasets:
	Berkeley Earth dataset aquired from Kaggel
    
### Charts:
	All charts extracted from eda and modeling
 

### Findings:
	- Global Warming does exist because land average temperature is increasing since 1770, especially the fastest tempreture growth have happened approximately from 1970 until 2015

	- spring season consistently the hottest season, then summer, followed by fall, and winter is the least hot season for earth temperature.
    
	- countries like ['Djibouti', 'Mali', 'Burkina Faso', 'Senegal', 'Aruba',
       'United Arab Emirates', 'Mauritania', 'Gambia', 'Niger'] has the heighest average tempreture, however countries like ['Poland', 'Switzerland', 'North Korea', 'Faroe Islands', 'China',
       'Austria', 'Falkland Islands', 'Lithuania', 'Belarus'] has the lowest average land tempreture.
       
### Baseline Models Performance:
	- RMSE of 6-months SMA Model: 8.54
	- RMSE of 12-months SMA Model: 6.62
	- RMSE of 12-months EWMA Model: 6.72
    
### ARIMA Model Performance:
	- ARIMA(12,1,11) RMSE: 1.43



