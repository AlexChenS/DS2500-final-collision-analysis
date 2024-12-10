
#### Data Source: https://catalog.data.gov/dataset/crash-reporting-drivers-data
### About the project
  Traffic collisions are a primary public safety concern, resulting in significant costs worldwide.
  The goal of this project is to build a predictive model to predict the severity of car crashes based on foreseeable conditions.
  By foreseeable, it implies that the feature should not contain any information that could only be collected at the scene at the accident. 
### Methodology 
  We devised two approaches of feature engineering to encode the data, the first one using ordinal encoding, and the later using one-hot encoding. Then, we trained a K-Nearest Neighbors model on both versions of the data. After hyper-parameter tunning, the approach using ordinal encoding won in accuracy measures. For more information see the notebook
### How to run
  This project is intended to be run on jupyter notebooks, and its list of dependencies are as follows:
  -pandas
  -numpy
  -sklearn 
  -seaborn 
  
