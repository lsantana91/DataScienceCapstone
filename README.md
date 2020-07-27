```markdown
## Author: Lisbeth Santana
## Florida International University

# Overview
	This project is focused on the prediction of tremor severity for patients suffering from Parkinson's disease. The data for this project is organized in 20-minute measurement windows of sensor data collected from smartphones and smartwatches. Each 20-minute interval is broken down into 30-second windows from which features are extracted and used to train a variety of general Machine Learning and ensemble models, of which XGBoost Regressors perform best. The extracted features seek to isolate the amplitude and frequency of any tremors present in these sub measurements in order to identify the severity of the same. 

# Data 
  The data for this project was obtained from the Dream BEAT-PD Challenge which was hosted in the beginning of 2020. Only participants have access to the data, however general methods can still be discussed. In general, the data was comprised of 20-minute intervals of accelerometer and gyroscope data, sampled at 50 Hz. Each of these measurements were labelled on a scale of 0 to 4, where 0 represented no tremors, and 4 represented the most severe ones. 
  
  These measurements were further broken down into 30-second segments, from which features were extracted in an attempt represent the amplitude and the frequency characteristics of Parkinson's disease tremors. The goal is to extract relevant features, create a new data set with these that could be used to train and test a variety of machine learning algorithms.
  


# Summary of Methods
A variety of methods were attempted which included kNN Classifiers, Random Forests and XGBoost. From these, the XGBoost Regressors outperformed the rest. However, after comparing multiple solutions to this problem, made available through the BEAT-PD Challenge, algorithms or techniques that include regression trees seem to work best with this type of problem. 
  


# General Findings
The biggest takeways from this project were the fact that every day devices have a large untapped potential. In this case, it was pertaining Parkinson's disease but this could be generalized to any disease or condition that affects movement. The fact of the matter is that smartphones, smartwatches and fitness trackers already have sensors built in them that can collect data that can be transformed and used for different purposes. In this case, features were extracted from the sensor data in an attempt to isolate tremors and predict their severity. 

```
