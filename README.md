# Air-Quality-Index-Prediction

When it comes to the problem, Air quality in urban India faces challenges from high pollutant levels due to industrial activity, vehicle emissions, and urban growth. Effective monitoring and prediction are hampered by the lack of continuous data, making it difficult to implement timely health and environmental safeguards. This project addresses these challenges by using machine learning to predict air quality indices, helping to inform better urban planning and public health responses.

To build our solution to this problem, first we have selected A dataset that includes air pollutants hourly data such as PM2.5, PM10, NO, NO2, CO, etc. from 2015 to 2020 of urban areas in India.
First of all, we have calculated AQI (Air quality index) for each row using each pollutant value. Then we analyse each pollutant's behaviour over time as well as pollutants' distribution in each city.
Then we extract time sereis features such as hour, day, week, etc. After that we used random forest regressor to predict AQI values for each city. 
