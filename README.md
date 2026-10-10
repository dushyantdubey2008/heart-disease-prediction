A machine learning web application built using Python, Scikit-learn, and Streamlit. This project uses a trained K-Nearest Neighbors (KNN) classification model to demonstrate a basic machine learning prediction workflow.
[Launch Heart Disease Prediction App](https://heart-disease-prediction-vzv5wjukwsro2ulbz8bzmb.streamlit.app/)
- Interactive web interface using Streamlit
- Prediction using a trained KNN model
- Input preprocessing using a saved scaler
- Consistent feature ordering for model input
- Web deployment using Streamlit Community Cloud
- Python
- Pandas
- Scikit-learn
- Streamlit
- Joblib
```
heart-disease-prediction/
├── app.py
├── KNN_heart.pkl
├── scaler.pkl
├── columns (1).pkl
├── requirements.txt
└── .gitignore
```
1. Clone the repository
```
git clone https://github.com/dushyantdubey2008/heart-disease-prediction.git
cd heart-disease-prediction
```
2. Install dependencies
```
pip install -r requirements.txt
```
3. Run the application
```
streamlit run app.py
```
1. Users enter the requested feature values.
2. The application prepares the input in the expected feature order.
3. The saved scaler preprocesses the input.
4. The trained KNN model generates a prediction.
5. The result is displayed in the Streamlit interface.
Dushyant Kumar Dubey
This project is for educational purposes only. It is not a medical device and must not be used to diagnose heart disease or make healthcare decisions. Consult a qualified healthcare professional for medical advice.
