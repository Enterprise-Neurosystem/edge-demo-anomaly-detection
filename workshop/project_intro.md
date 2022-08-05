# Introduction

## Sensor Failure Prediction 
Failure prediction in real time on time series data (wind turbine) can be realized with the use of Open Source. This project will design docs/code that will injest raw sensor data and end up with a real time graph that shows alerts warning that a mechanical failure is imminent.

A data collector will be used to receive raw sensor data and then place the data into a data storage unit. All of the new raw sensor data are associated with the timestamp of when the sensor data was generated, thereby forming what is called a time series. The data collecotr then makes an API call to a web application that puts the new data into a form that enables a training Machine Learning model to make a binary classification (Normal or Not Normal) prediction. A real time series graph is then updated with the prediction, and the graph is pushed to a browser that is connected to the web applicaiton.

## Anomaly Detection Demo
Demo application that displays web user interface to allow users to generate a graph displaying pump data and associated anomalies. The demo utilizes synthetic data that mimics real life sensor data.


---

|  | **Resource**                                  |                                                              Links                                                         |
|-:|:----------------------------------------------------:|:---------------------------------------------------------------------------------------------------------------------------|
| 1| Synthetic Data                                  | [Click Here](../static/casing1correcteddate.csv)                                                                     |
| 2| Web UI (html)                              | [Click Here](../templates/main.html)                                                                                   |
---
