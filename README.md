# 🧠 Customer Churn Prediction (ANN)

This project uses an Artificial Neural Network (ANN) to predict whether a customer is likely to churn based on demographic and account-related features. It includes a trained model and a Streamlit web app for making live predictions.

🔗 **Live App**: [Open on Streamlit](https://ann-customer-churn-kkxcgp3sww3qkpfwczmqud.streamlit.app/)

---

## 📁 Project Structure

- `app.py` – Streamlit app for live churn prediction.
- `Churn_Modelling.csv` – Dataset used to train the model.
- `experiments.ipynb` – Jupyter notebook for model training.
- `predictions.ipynb` – Notebook for testing predictions.
- `model.h5` – Trained Keras model.
- `label_encoder_gender.pkl` – Saved label encoder for gender.
- `onehot_encoder_geo.pkl` – One-hot encoder for geography.
- `scaler.pkl` – Standard scaler for feature normalization.
- `requirements.txt` – Python dependencies.
- `runtime.txt` – Python version pinning (e.g., `python-3.10` for Streamlit compatibility).
