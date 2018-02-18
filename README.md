IDAS - intelligent driver assistant for Accident Prediction
===========
Java-based app could read video from camera or stored videos and after selecting ROI(region of interest)
user can select appropriate algorithm for detecting danger situations on the road.

### Algorithms
SURF - for feature detection
DBSCAN for cluster detection from SURF output
CNN from tensorflow for classification of object
Fuzzy rules for inference the type of predicted accident