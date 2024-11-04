IU INTERNATIONAL UNIVERSITY OF APPLIED SCIENCES. 
Project: From Model to Production (DLBDSMTP01). 


Task 1: Anomaly detection in an IoT setting (Spotlight: Stream processing).  

Problem Statement.
A cutting-edge modern factory is producing machine components for wind turbines. The factory
is equipped with numerous sensors which track the production cycle. The factory managers can
oversee the numeric values in a BI dashboard. In addition to this, they would like to be
informed by a decision support system when patterns emerge in the sensor data, implying that
something has gone wrong. As the data scientist for this project, you are assigned to develop and
implement an anomaly detection system that integrates with the productive system. You can
rely on the expertise of the shop floor employees who have been working at the production site
for a long time and have gathered valuable domain knowledge. In close consultancy with the
shop floor employees, it has become clear that temperature, humidity, and sound volume are
good indicators for an anomaly in the production cycle and a faulty produced item. You build a
simple machine learning model in Python which uses these features to predict an anomaly
score for each made item. This model should not be very elaborate, but the focus of your task is
to design a model so that it is easily implemented in the productive system. Your system must
be able to process data streams, as the sensors in the factory measure data continuously. Your
implemented model should take these measurements over a standardized API and respond
with a prediction score for an anomaly. Your system must be easily monitorable, maintainable,
scalable, and adaptable to new data.
1. Design the conceptual architecture of your system. By doing so, consider data ingestion,
processing, and handling requests to the prediction model as a service. Draft a visual overview
of your architectural design, showing which data and processes are handed over by which
application to the next. This will also guide you through the next steps of your project.
2. Choose an open data source that can serve as sample data for your project. A good starting
point for your research are open data science competition websites, such as Kaggle.
Alternatively, you can also produce your own fictional sample data. As you have to simulate
continuous streams of data, you basically have three options: 1) Run an application on your
local machine which produces a continuous stream of simulated sensor data, 2) find a
continuous open stream of sample data online, or 3) use a static opendata set and simulate its
continuous nature by manually updating the data and monitoring the changes in your system
3. Build a simple anomaly detection model using Python. The model should be trained by the
simulated sensor data you acquired in the second step. Do not put too much effort into building
this model, and just make sure that it performs the task at hand and check basic statistical
measures.
4. Package your model in a way that it can take (simulated) sensor data over a standardized
RESTful API and respond with a prediction for an anomaly. You might want to use Python
libraries for this, such as Flask or mlflow. A good starting point for this step is the
documentation of the respective Python libraries. This will be the most work-intensive step of
your project.

CONCEPTUAL ARCHITECTURE 



















































