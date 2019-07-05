# call-for-code-2019
This is the repository for the solution offering for Call For Code 2019
Project Title
Gas Leakage Notification App

Project Description

Our team has built the “Gas Leakage Notification” app which will be providing prior notifications to the people and utility departments during the natural calamities disasters like wild fire or volcano eruptions, if there is any gas leakage is going to happen with heavy pressure based on the prediction of the weather. Below is the architecture diagram on how the application is acting and responding during the disaster time

Current Problem - 

During natural calamities disasters like wild fire or hurricanes or volcano eruption, it was observed in many places that the gas pipes are getting leaked due to heavy pressures and people are not getting prior notifications about the leakages especially from the utility departments and they are getting into risk and sometimes huge damages in surrounding places and life risk.


Solution Description - 

The “Gas Leakage Notification” app is an app deployed on cloud store and will be deployed on utility department site and even people can install the app on their mobile or tablet or wearable devices. This app is frequently talking to IBM “Weather API on Cloud” and check any prediction on hurricane or wild fire or volcano eruption in the future and frequently checking the pressure inside the gas pipes. If the app suspect the pressure is beyond or at par of the risk level, then immediately it will talk to “Gas Leakage API” which is newly designed API on IBM cloud. This API will talk to Utility supply department database to compare the gas supply pressure level and pressure predicated from the Weather API. Then immediately it starts running the predictive analysis algorithms and update the information on live DB which is IBM DB on cloud. And it will start send the alerts/push notifications to the users and utility departments and simultaneously sending the leakage information to IBM Watson BOT to update the media. During the incident time, if the utility department captures any photos, videos and analysis information and if the network is available, it will update into live database otherwise it will store the data into offline DB and sync to live DB once the network is available.


Included Components - 

IBM Weather API
IBM CloudantDB
IBM Watson BOT
Push Notifications API on cloud
PouchDB
New API hosted on IBM Cloud
New Utility DB on IBM Cloud

Featured Technologies - 

1.	New API is built using spring boot on IBM cloud
2.	Angular 6 used for responsive web app
3.	Python scripts used for predictive analysis

Steps - 

Currently we are facing few technical challenges in calling the API on cloud from our ODC so we could not able to complete the POC to upload. Hence we are going with our proposed solution in the architecture diagram artefact. Unfortunately there is no API available on IBM cloud to talk with utility department database so we have to build a new API and need to find the source for utility department data.

Results - 

The proposed solution is going to work both on network and off network and it will be useful for the utility departments to take necessary actions on gas leakages during the disaster time
