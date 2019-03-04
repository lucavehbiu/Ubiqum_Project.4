# Wi-fi indoor localization, Universitait Jaume, Valencia

_Indoor localization techniques have exponentially 
risen the last decade, given the inability of GPS 
signal to track us down inside buildings._

* Even though, that might fuel in the paranoia sometimes it is very useful to know exactly where you are in a big building such as museums, shopping malls and university campuses. 

* Building on the previous literature, the method used in this project is that of 'fingerprinting'. 

* The training set was created by the data collected through an app, tha recorded someone's location when they connected to the wireless network of the building. By having an extensive knowledge of all possible points inside the building and all their signal strengths toward the nearest Wi-fi extenders near them a k-nn model was used on it to predict building (100%) then floor (96%) and Longitude & Latitude (6.5 meters, average error). 

* This model was validated on a real-life example (people wandering around the libray) without telling them where to connect to the Wi-fi.
