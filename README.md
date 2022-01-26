# Problem Statement:
Garbage Management and Collection in Cities, Town and Villages is a major concern and emerging problem in Smart City paradigm. Also lack of proper resource distribution in the process of Garbage collection is great risk to sanitation, cleanliness and health. 
# Theme: Internet of Things
# Objective:
To efficiently automate the segregation of waste based on its type, i.e. biodegradable or not, in order to ensure proper waste disposal for healthier environment.
# Description
This project automates the task of waste segregation in public dustbins by classifying waste as either biodegradable or non-biodegradable. We use a Raspberry Pi along with a servo motor, IR, Ultra-Sonic Sensor, Pi Cam and a server(laptop) to accomplish the project.

The project has been implemented as an IoT system which captures images through the Pi and sends it to a server for processing. On the server, we use CNNs for the Machine learning/Image processing algorithms, which are used to identify type of waste that was dumped. The server communicates back to the Pi and the Pi actuates accordingly by turning the servo motor and thus dumping the garbage to either the biodegradable or non-bioderadable side. We use an ultrasonic sensor to detect the level of garbage accumalated in the bin.

If the bin has been filled, we use Twilio's API to send out a message, informing that the bin is full and has to be replaced.
# Pros:
-Waste is classified as per its type. -Manpower is reduced;the waste need not be sorted by a person. -Fuel is saved.The content in each bin is analyzed and based on that, the call for transportation is made.
# Cons:
-The model is costlier than a normal plastic dustbin. -Mixed waste cannot be classified efficiently upto a certain extent. -In order to classify the waste efficiently, the waste should be scanned in ample lighting conditions
# CLEAN-IT
 waste monitoring system is a role based system having three roles admin, driver and a citizen. Admin has a dashboard from which admin can add resources such as drivers, bins, depot, dumping ground and vehicles. Admin will have facility of viewing the current data in the system and monitor the drivers in real time.
 
 The new bin location can be added by just clicking on the map or writing the address of the actual location. Its capacity and height needs to be entered as those parameters will be used to calculate real time garbage level of the bin.
 
 The bin status will be shown to admin wherein bins are classified into three categories based on the level of garbage. Red, yellow and green bins represent overfilled bin, normally filled bin and underfilled bin respectively
 
