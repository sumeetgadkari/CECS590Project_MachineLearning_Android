# CECS590Project_MachineLearning_Android
A group project developed by Me, Pratik Borole, Makrand Patil, Aishwariya Talathi.

MediEase is an android application to recommend best hospitals in an area using Machine Learning. A user selects a location on his android phone with the help of google maps and then gets a response from server hosted on AWS in the form of list arranged in descending order according to hospital rankings. The application also provides the options like scanning a prescription, storing the same prescription on server, alarm manager to notify intake time. We also developed our own platform to help user convey his thoughts on a hospital after his visit.

I primarily worked on yelp dataset collection, preprocessing, model development for sentimental analysis of hospital review and then deploying this trained model on AWS EC2 instance. When a request is made to a server to rate hospitals in a area, then real time reviews of hospital were fetched using Google places API and each review was run against model to predict its sentiment. Python was used for Machine Learning while PHP for API call handling.
