# CMPE281-SensorDataProject
Monitor the Ocean atmosphere using sensor data

# CMPE281-SensorDataProject
Monitor the Ocean atmosphere using sensor data

Project Objectives:
This project is designed to develop, implement, and validate a mobile sensor cloud engine for environment sensors to allow San Jose city residents to learn their city environments. 

Description: Our mobile sensor cloud consists of the following components: - 
Back-end mobile cloud server- which provides service management, monitoring, and dashboard. 
Mobile sensor hub - Each hub can track and report sensor status, report, and collect the live sensor data. Each sensor simulates the data collection, health-check, monitoring of their states. 
Sensor resource manager – This allocates and manages one or more sensor hub (s) based on users’ on-demand requests.
 Sensor data access manager – This supports user to access the existing sensor data
 Sensor data collector – This collects sensor data based on pre-defined schedules and allocated sensors for each user. 
Sensor data repository – we have used mongoDB as a sensor data store.
Dashboard user interface – This component the user interface to support the user and system interactions.


List of functionalities:
Creation of user and login
Steps to create user:
Click on Sign up button 
Fill all the details in the sign up page
Click on signup button. You will get a successful signup message if you have 
You can use the credentials you just created to login to application.
Verification
If log-in was successful, a user dash board page will be displayed.

Login to application as a User and click on “Request Water Quality” card. 
Select the location and sensor name from the drop downs.
Select the TO and FROM dates and click on Submit button.
This will allow the user to check the historical data for different sensors at different locations.

Click on View sensor info on map.
You will be able to see the information of the sensors at different locations on the map.

Once you are done viewing the data proceed to pay the Bill.
The user is charged based upon the numbers of requests he is making. Care is taken such that if the user has requested the same data multiple times he will be charged only once.

Login as an Admin
When the user logins as an admin he will be able to Add sensors, Manage sensors and will also be able to view all the users using the sensors.

Steps to use the Admin Dashboard:
Login to the application as admin.
Click on “Add Sensors” card layout. Fill up all the details and click on submit. If the sensor is available, then the admin can add the sensor successfully. A message will be displayed telling the admin if the sensor is added successfully or not.

Similarly, Admin can keep a track of the Users using different sensors. When the admin clicks on this card he can see the user details.

The admin can delete, activate and deactivate the sensors when he clicks on Manage Sensors. Corresponding messages will be displayed to the admin regarding the activation and deactivation status of the sensor.

Technologies used:
MEAN stack, Leaflet APIs for maps, HTML5 templates for front end development.


Team Members:
Shruti Kangokar(Back end server design, Data base design, user module, deploying the app to Amazon AWS cloud , Testing)
Swathi Sudarshan(Admin module, Back end server design, Data base Design, code integration)
and Pramod Kasibhatta(front end template and documentation)
