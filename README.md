# CTP Final Project
### Nikola Baci and Aaliyah John
### May 28th, 2021

## Overview
Exoplanets are planets beyone our solar system. In 2009, NASA launched the Kepler mission, a space telescope that would serch for exoplanets. Our project uses the [Kaggel](https://www.kaggle.com/nasa/kepler-exoplanet-search-results) dataset which was last updated in 2017. In this dataset, we can find __CONFIRMED__, __FALSE POSITIVES__, and __CANDIDATES__ KOIs (Kepler Object of Interest).

CONFIRMED  = the object has passed all the tests and it is confirmed to be a planet  
FALSE POSITIVE = the object has failed at least one test, thus it it not a planet  
CANDIDATE = the object is undergoing investigation, the decision to be determined  

## Goal
The goal of this project is to train a machine learning model on the labeled data, namly the CONFIRMED and FALSE POSITIVE KOIs, and use this model to make prediction of the label of the CANDIDATE KOIs. The notebook can be found in `koi_future_prediction_dt_model.ipynb` and the Kaggel data in `cumulative.csv`.

## Results
After we obtain the predictions from our Decision Tree model, we compare the answers with the latest updated database from NASA in `final-data.csv`. We sucessfully predicted the future 115 times. For more information of the procedure we followed you can check out the [jupyter notebook](https://github.com/nikolabaci98/kepler-exoplanet-search-results/blob/main/koi_future_prediction_dt_model.ipynb) and our [flusk app](https://exoplanet-exploration.herokuapp.com/).
 
Please feel free to give your feedback about our work.



