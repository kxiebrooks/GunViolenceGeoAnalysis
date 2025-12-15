# GunViolenceGeoAnalysis
#### Gun violence is a significant public safety concern in the United States and around the world. Understanding patterns and predicting high-risk areas can help policymakers, law enforcement, and communities take preventive measures.

#### This project aims to predict the risk of gun violence using historical geocoded incident data and spatial features. By identifying areas with a higher probability of injuries or deaths, we can visualize risk clusters and potentially inform interventions.

#### The dataset used is GVA (Gun Violence Archive) 2015–2021, which includes: Geocoded incident locations (latitude, longitude), Date and time of the incident, Number of people killed (n_killed), Number of people injured (n_injured), Some preprocessing steps include: Filling missing values for n_killed and n_injured with 0, Dropping unnecessary columns like state, city, address, and URLs, Creating a GeoDataFrame for spatial operations

#### In this project 3 models was being used, one is KNN classfier, one is Random forest regresser and one is Pipeline. KNN is being used to incorporate more geospatial features in order to do better predictions. Both Randomforest regresser and Pipeline were approches to estimate the accuracy of the prediction with Pipeline containing a whole US map between long -125 and -75 with the pridiction of gun violence death. 

#### KNN model produced visualization is based on its high 58.7% accuracy of prediction which is able to produce the local gun violence cluster and places that are high risk