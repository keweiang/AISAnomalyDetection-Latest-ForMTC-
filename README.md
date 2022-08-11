# AISAnomalyDetection-Latest-ForMTC-
This folder contains the python code to clean raw AIS data in text file format and perform anomaly detection by classifying the vessels into normal, abnormal and power outage classes.

>>>>>>>>>>>>>>>>>>>>>>>Instructions to run the codes available in google colab<<<<<<<<<<<<<<<<<<<<<<<<<<<

TryCleanAISdata.ipynb (Use to generate cleaned dataset from raw text files)
- upload AIS raw data in text file format into a Google Drive folder
- Open TryCleanAISdata.ipynb> Runtime > Run all > Select the Google account that contains the raw data folder
(Cleaned dataset will automatically downloaded to computer after done cleaning)

AISAnomalyDetectionSystem.ipynb (Get cleaned dataset to perform anomaly detection by classifying vessels into normal, abnormal and power outage classes)
- Upload the cleaned dataset generated from TryCleanAISdata.ipynb to this colab notebook by clicking on the     folder symbol on your left, then drag the dataset to the section on your left
OR
- Upload the cleaned dataset from TryCleanAISdata.ipynb to Google Drive (same Google account with previous   one)
- Runtime > Run all > Select the Google account that contains the dataset

- Wait for the result
- 
>>>>>>>>>>>>>>>>>>>>>END<<<<<<<<<<<<<<<<<<<<<<<<<<<
