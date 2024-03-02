## Solar Energy (Kaggle compmetition)

**Use ML to predict solar radiation levels**

_(Competition part of Ironhack Data Analytics bootcamp)_

# Summary

The goal of this competition is to train the best Machine Learning model to predict solar radiation, using RSME as error metric. We were all provided two CSV files, one for training and testing, and another one for the final prediction. 

Throughout the competition we could upload a maximum of 5 results per day, and we could only see RSME for 70% of the final data. The remaining 30% was only inlcuded once the competition was closed, and we could see our real RMSE values.

The data provided was:

- Radiation (watts/m2) - taget
- Temperature (Fahrenheit)
- Humidity (%)
- Pressure (mmhg)
- WindDirection(degrees)
- Speed (milles/hora)
- Sunrise/sunset (Hawaii time)
- UNIXTime (TimeStamp, second since 01-01-1970)
- Data (date)
- Time

# Process

For each modele trained, I followed the same process: updloading, cleaning and processing the data, selecting different formats, units and columns for each iteration. For most of them I trained several models at the same time to compare results, althoug I always obtained the best ones using RandomForestRegressor for the sklearn library. 

You can see all the process and interations the file 'energia_solar.ipynb'. Training and test data are in 'solar_train.csv' and 'solar_test.csv' files. 

