# Anomaly Detection in Air Traffic Data Streams

Applying anomaly detection approaches to the sector of aviation carries the potential to save millions of lives. Utilizing well-researched anomaly detection algorithms like isolation forest and combining them with techniques like sliding windows, this project aims to produce an efficient method to identify potential anomalies in air traffic data streams. It trains the model on an initially unlabelled dataset and attempts to pinpoint the specific locations and frame rates of the detected anomalies. By addressing anomalies in aviation data, the study endeavours to contribute to the enhancement of safety and efficiency within the aviation sector.

## Dataset
Flight Data Tail 682 By Bryan Mathews (https://c3.ndc.nasa.gov/dashlink/resources/659/)

## Environment For Code
We are working on the Python (Jupyter Notebook) environment and imported some of the libraries to run our code.
> Files used for code: 
682200107170331.csv (Original File)
682200107170331_fill_zero.csv (Filled Zero values)
682200107170331_fill_knn2.csv (KNN imputed with Neighbour value 2)
682200107170331_fill_knn3.csv (KNN imputed with Neighbour value 3)

> Libraries Used:
	     1. Tensorflow Library  for Autoencoders
	     2. Pandas, Numpy, Matplotlib, Seaborn
	     3. Keras Library for LSTM
	     4. SKlearn Library to import the pre-defined models
