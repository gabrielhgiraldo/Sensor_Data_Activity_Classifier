# Device Sensor User Activity Random Forest Classifier
### Loading Data
Dataset taken from http://archive.ics.uci.edu/ml/datasets/Heterogeneity+Activity+Recognition#
Be aware that when unzipped, data is ~3.3gb!
data not included in repository(just download it from link above)

### Try your own data!
* download the SensorUDP app from
https://play.google.com/store/apps/details?id=com.ubccapstone.sensorUDP&hl=en_US  
* run The Live_Sensor_Streaming jupyter notebook
* follow instructions and enjoy! (due to controlled conditions in the dataset, it only works if the back of the phone is facing downward, I try to do some coordinate system transformations using the rotation sensors, but haven't completely nailed it down)

### Further Consideration
* Get a more representative dataset
* Different train test split (time split/leave one out?)
* Include more activities
* Include more sensors if accelerometer isn’t sufficient
* Include more time and frequency features
