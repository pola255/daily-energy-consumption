# Daily energy consumption in London: Time series with Prophet

The data provided is a time series from smart-meters in London from end of 2011 to 2014. It contains the daily consumption (kWh) averaged over several households in London.

The last timestamp for which consumption is available is January 31st 2014.

It was built a forecasting model that can predict the consumption for February 2014(excluding 28th, so from the 1st to the 27th). It was used prophet library, before was recognized seasons intervals and outliers like the winters and 2012 year.
