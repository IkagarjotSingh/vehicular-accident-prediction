# vehicular-accident-prediction
Created a predictive model based on historical weather data, weather and road condition alert tweets, and quadrant wise (NW,NE,SW,SE) traffic incident reports by the City of Calgary. 

We used Weather Data from Environment Canada Data Archive, Traffic Incident Data from The City of Calgary, 511 Alberta a free traveller information service, operated by the Government of Alberta's Twitter account. Tweets were extracted via official Twitter API. 

The datasets were merged based on the timestamp.

We used Logistic Regression Multinomial Classification, Random Forest Classifier and XGBoost as baseline and a ensemble model to predict the probability of accident for each quadrant per data point.
