1. Combine and Clean Data:
Grouped the transactions by date and calculated total daily revenue.
Removed rows with missing or incorrect data.
2. Understand the Revenue Pattern:
Plotted the daily revenue to observe trends.
Used a statistical test (ADF test) to check if the data was stable over time.
3. Prepare Data for Modeling:
Since the data was not stable, we applied a method called "differencing" to make it stable.
4. Build a Forecast Model:
Chose a basic model called ARIMA(1,1,1) which learns from past revenue values and their changes.
Trained the model on our cleaned and processed daily revenue data.
5. Predict the Future:
Used the model to forecast the revenue for the next 7 days.

