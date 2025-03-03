# analyze-visualize-model-telecom-italia
Python (pandas, statsmodels, etc.) to read, aggregate, store, analyze, and model Telecom Italia data from CDRs.

The data used in the following analysis was retrieved from dandelion.eu.  It is based on Call Detail Records (CDRs) generated by the Telecom Italia cellular network over the city of Milano (or Milan).  "Activities"indicated in the dataset measure "levels of interaction of the users with the mobile phone network; for example the higher [ ] the number of SMS sent by the users, the higher [ ] the activity of the sent SMS. Measurements of call and SMS activity have the same scale (therefore are comparable)."

telecom_daily_heatmap.py - produces a heatmap (call_in_mgrid.png) showing call "hot spots" in Milan during a given day.

telecom_time_series_store.py - produces a time series for calls into and out of Milan during December 2013.

telecom_time_series_analysis.py - models the time series produced by telecom_time_series_store.py via ARMA.
