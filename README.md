# Steady/Moving State Prediction

## ABOUT THE PROBLEM

Datasets contain information gathered from sensors like accelerometer,gyrometer and magnetometer at steady and moving state of the vehicle.The data is processed using filters.
The motive of the project is to develop a method so that once the information from the sensors is given ,we should be able to predict the state of the vehicle with very good  and reliable accuracy.

### STEPS FOLLOWED:

1)Datasets are imported and visualised to gain the insights from the data.We are interseted only in the filtered values.Hence ,selected the x-y-z accelerations gathered by accelerometer.

2)A deterministic algorithm is applied based on minimum and maximum thresholds.Tested on the data and calculated its accurcay.But the accuracy score is not satisfactory.

3)A Random Forest model was further deployed which gave the maximum and satisfactory accuracy.


#### OUTPUTS

1) The deterministic algorithm yielded accuracy of only 77%.

2) Random forest model yielded the accuracy score of 98% which is quiet high.

