# Fever-detection-using-ML
Fever prediction model using high-frequency real-time sensor data

Code Description :

1. Normalization.py
The script normalize the vital columns of the dataset.

2. Medication.py
The script creats a python dictionary which has the pataient wise data for the time offset when the pataient was given antipyretic doses.

3. Preprocessing.py
The script takes vital data of pataients and saves the features extracted from the data.

4. Models.py
The script takes the data created by Preprocessing.py and feed it to different models, so that we can compare differerent models on the basis of F1 score and AUROC score models are getting.
