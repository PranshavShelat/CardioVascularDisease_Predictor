# CardioVascularDisease_Predictor

heart_disease_model.pkl: trained logistic regression model saved using joblib  
cardio_train.csv: Data set used for model training  
MainNotebook.ipynb: Jupyter notebook containing:  
    Data exploration and visualization  
    Feature selection and preprocessing  
    Model training and evaluation  
    User input and prediction logic  

**How to run:**  
Open notebook `"heart_disease_prediction.ipynb"` in Jupyter or Google Colab  
Import libraries and run all the cells  

**Load model with:**  
```python
import joblib  
finalModel = joblib.load('heart_disease_model.pkl')
