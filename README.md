# edge-demo-anomaly-detection

## Project Desctiption

The app is deployed using minimal Web UI and utilizes synthetic data that mimics real life sensor data. Once deployed, a start and stop button can be used to generate a graph displaying pump data and associated anomalies. 

All source code and data used for this demo can be found in this repository: 

|  | **File/Folder**                                  |                           Description                                                         |
|-:|:----------------------------------------------------:|:------------------------------------------------------------------------------------------|
| 1| [.s2i](./.s2i)                 |      Produces a ready-to-run image |
| 2| [managers](./managers)      |     Contains data managers (prepare data for graphing)   |
| 3| [static](./static)                 |      Contains synthetic data used in the demo |
| 4| [templates](./templates)                 |      Contains main.html (defines app framework) |
| 5| [workshop](./workshop)                 |   Contains demo instructions    |
| 6| [config.py](./config.py)    | Establishes 2-way socket communication |
| 7| [requirements.txt](./requirements.txt) | Specifies default required packages |
| 8| [wsgi.py](./wsgi.py)      |     Gunicorn server, calls main.html and obtains data     |


## Tutorial

By the end of this tutorial you will learn how to create, containerize, and deploy the Anomaly Detection demo application that allows the user to visualize pump data along with associated anomalies. 

[Begin the tutorial.](./workshop/deployment.md)

## Contact

areznik@redhat.com for information regarding this project.
