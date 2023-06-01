# Week_11_Challenge
USYD FinTech Course Week 11 Challenge Repo

*Language: Python, Createrd in Google Collaboratory*

## Step 1:  

### Step 1
![Search Trends for MercadoLibre May-2020!](/images/bokeh_plot_search_trends_May_2020.png)

### Step 2
**Question:** Did the Google search traffic increase during the month that MercadoLibre released its financial results?
**Answer:** *The search traffic inceased by 3008.5 during the month of Mayb when financial results were released*

## Step 2:

### Step 1
![MercadoLibre Average Hourly Search Data by Day of Week!](/images/bokeh_plot_hourly_search_by_dow.png)

### Step 2
![Heatmap of MercadoLibre Sreach Trends: Day of Week vs Hour!](/images/bokeh_plot_hourly_dow_heatmap.png)
**Question:** Does any day-of-week effect that you observe concentrate in just a few hours of that day?
**Answer:** *Search trends seem to be more concentrated in the early/late hours of the day and mostly during the start of the week.*

### Step 3
![MercadoLibre Average Hourly Search Data by Week of Year!](/images/bokeh_plot_hourly_search_by_woy.png)
**Question:** Does the search traffic tend to increase during the winter holiday period (weeks 40 through 52)?
**Answer:** *The search traffic does ineed increase during the winter holidays, dropping over the Christmas/New Year break before increase again in January.*

## Step 3:

### Step 1
![MercadoLibre Stock Closing Price 2015-2020!](/images/bokeh_plot_mercado_close.png)

### Step 2
![Closing Price and Search Trends data for MercadoLiber Jan-Jun 2020!](/images/bokeh_plot_search_Jan-Jun_2020.png)
![Closing Price and Search Trends data for MercadoLiber Jan-Jun 2020!](/images/bokeh_plot_close_Jan-Jun_2020.png)

**Question:** Do both time series indicate a common trend that’s consistent with this narrative?
**Answer:** *The drop in March 2020 in stock price and the drop in search trends as well as the spikes in May seem to indicate a common trend consistent with the narrative.*

### Step 3
![MercadoLibre Stock Volitity!](/images/bokeh_plot_stock_volatility.png)

### Step 4
**Question:** Does a predictable relationship exist between the lagged search traffic and the stock volatility or between the lagged search traffic and the stock price returns?
**Answer:** *There seems to be a weak negative correlation between lagged search traffic and stock volatility and much smaller positive correlation with stock returns.*

## Step 4:

### Step 2
![Prophet Predictions for MercadoLibre!](/images/Prophet_Predictions_MercadoLibre.png)

**Question:**  How's the near-term forecast for the popularity of MercadoLibre?
**Answer:** *It is expected that the popularity will increase based on the above graphs*

### Step 3
![Prophet yhat, yhat_lower, and yhat_upper columns over the last 2000 hours!](/images/bokeh_plot_Prophet_yhats.png)

![Prophet Forecasted Components!](/images/Prophet_Components.png)

**Question:** What time of day exhibits the greatest popularity?
**Answer:** *The start/end of the day show the greatest popularity*

**Question:** Which day of week gets the most search traffic? 
**Answer:** *Tuesdays recieve the most search traffic*

**Question:** What's the lowest point for search traffic in the calendar year?
**Answer:** *Search traffic is the lowst in October*

## Step 5:
### Step 1
![MercadoLibre Sales Prophet DataFrame!](/images/bokeh_plot_MercadoLibre_Sales_Prophet_DataFrame.png)

### Step 2
![Future Prophet Prediction Components for MercadoLibre!](/images/Future_Predictions_Components.png)

**Question:** For example, what are the peak revenue days? (Mondays? Fridays? Something else?)
**Answer:** *The peak revenue days are Mondays, Tuesdays and Wednesdays*

### Step 3
![Future Prophet Predictions for MercadoLibre!](/images/Future_Predictions_Plot.png)

### Based on the forecast information generated above, produce a sales forecast for the finance division, giving them a number for expected total sales next quarter. Include best and worst case scenarios, to better help the finance team plan.
**Answer:** *Based on the predictions of the Prophet machine learning model, the most likely sales forecast for the next quarter will be ~970 with the best case being ~1052 and worst case being ~888.*




# Resources:
- https://www.stechies.com/compare-lists-python-using-set-cmp-function/
- https://www.markdownguide.org/basic-syntax/
- https://pandas.pydata.org/docs/reference/api/pandas.DataFrame.shift.html
- https://pandas.pydata.org/docs/reference/api/pandas.DataFrame.corr.html
- https://stackoverflow.com/questions/11346283/renaming-column-names-in-pandas
