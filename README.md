## Classify Candidate Exoplanet Based on Kepler Observations
Evaluating different machine learning model to classify candidate exoplanet from NASA raw data-set

### Data Source
Kaggle : https://www.kaggle.com/nasa/kepler-exoplanet-search-results

### Background
Over a period of nine years in deep space, the NASA Kepler space telescope has been out on a planet-hunting mission to discover hidden planets outside of our solar system. Kepler has verified 3000 exoplants as of october 2017. The dataset is a cumulative record of all observed Kepler. The records includes approximately 10,000 exoplanet candidates Kepler has taken observations on. 
This dataset has an extensive data dictionary, which can be accessed here (https://exoplanetarchive.ipac.caltech.edu/docs/API_kepcandidate_columns.html).

### Goal
Evaluate different machine learning model to predict new exoplanets based on Kepler observation data
Identify a model with best prediction capacity

### Method and Observation
Explored Logistic Regression, Support Vector Machine, and Deep-Learning model to classify the candidate exoplanets. Model accuracy was examined by fitting the test data. Deep Learning model has the highest accuracy 0.89 and it was also better at predicting new exoplanets.

### Prediction
Out of 20 test data the model only misidentified one data <br>
![4-scatter](Images/model_predict.PNG)

### Repository navigation
Models_evaluate consist of all the jupyter notebooks with model evaluation<br>
1) DeepLearning_model.ipynb<br>
2) logistic_model.ipynb<br>
3) SVM_model.ipynb<br>

Saved models for future use<br>
1) deeplearning_model.sav <br>
2) logistic_model.sav<br>
3) svm.sav<br>

Data<br>
1) exoplanet_data.csv<br>





