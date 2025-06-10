# CardioVascularDisease_Predictor

heart_disease_model.pkl: trained logistic regression model saved using joblib
cardio_train.csv: Data set used for model training
heart_disease_prediction.ipynb: Jupyter notebook containing: 
                                Data exploration and visualization
                                Feature selection and preprocessing
                                Model training and evaluation
                                User input and prediction logic


**How to run:**
Open notebook "heart_disease_prediction.ipynb" in jupyter or google colab
Import libraries and run all the cells

**load model with:**
import joblib
finalModel=joblib.load('heart_disease_model.pkl')

Provide user input manually 
Run prediction set to get output
