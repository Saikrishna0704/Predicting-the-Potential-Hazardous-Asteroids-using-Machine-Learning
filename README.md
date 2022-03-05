# Predicting-the-Potential-Hazardous-Asteroids-using-Machine-Learning

There are numerous asteroids that are orbiting randomly in space. Few of them may get close to the earth's orbit and can be harmful at some point in time. It is important to have the foresight to avoid any harm. Ground-based telescopes operating in infrared spectrums and tracking campaigns are the sources of asteroid classifications. As there is a great advancement in the field of machine learning in terms of predicting ability and efficiency of the algorithms, we can apply machine learning to classify the asteroids as potentially hazardous asteroids or non-hazardous asteroids. The main objective of this work is to train a machine learning model with the historical data to identify the pattern of the independent features in the data and predict whose risk factor is unknown as potentially hazardous asteroids (PHAs). The dataset used to train the machine learning model is taken from NASA Jet Propulsion Laboratory Small-Body Database Search Engine.

# Envirnoment

* Colab
* CatBoost
* XGBoost
* Numpy
* Pandas
* Seaborn
* Matplotlib
* Scikit-learn

# Setup

```
$ !pip install catboost
$ !pip install xgboost
```

# Dataset

The training and testing dataset was created by taking the data from the NASA Jet Propulsion Laboratory Small-Body Database Search Engine on 27thApril 2021. All samples are stored in the form of a CSV file and the dataset consists of 25708 rows × 9 columns. The columns of the dataset have the information related to object fields, orbital and model parameters of the asteroids.

| Column name   | Column Description                                    | 
| ------------- |:-----------------------------------------------------:| 
| full name     | Object full name/designation                          | 
| H             | Brightness                                            |   
| PHA           | Potentially Hazardous Asteroids,flag (Y/N)            | 
| e             | eccentricity                                          |  
| a             | semi-major axis(au)                                   | 
| q             | perihelion distance(au)                               |   
| i             | inclination; angle with respect to x-y ecliptic plane | 
| moid          | Earth Minimum Orbit Intersection Dis-tance(au)        | 
| class         | Orbit classification                                  | 
