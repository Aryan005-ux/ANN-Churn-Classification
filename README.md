# ANN Churn Classification

## Live Demo

The model is deployed using Streamlit and can be accessed here:

**Streamlit App:**
https://ann-churn-classification-jod5dt8uynxuumbjbnmqyn.streamlit.app/

This web application allows users to input customer information and predict whether the customer is likely to churn.

---

## Overview

This project predicts **customer churn** using an **Artificial Neural Network (ANN)**. Customer churn prediction helps businesses identify customers who are likely to stop using their services.

The model was trained using customer banking data and deployed using **Streamlit** to create an interactive prediction interface.

---

## Features

* Interactive web interface using Streamlit
* Real-time churn prediction
* ANN deep learning model built with TensorFlow/Keras
* Data preprocessing using Scikit-learn
* Feature encoding and scaling

---

## Technologies Used

* Python
* TensorFlow / Keras
* Scikit-learn
* Pandas
* NumPy
* Streamlit

---

## How the Model Works

1. User enters customer details in the Streamlit app
2. Data is preprocessed (encoding + scaling)
3. The trained ANN model processes the inputs
4. The model outputs the **probability of churn**

---

## Project Structure

```
ANN-Churn-Classification
│
├── app.py
├── model.h5
├── scaler.pkl
├── label_encoder_gender.pkl
├── onehot_encoder_geo.pkl
├── requirements.txt
└── README.md
```

---

## How to Run Locally

Clone the repository:

```
git clone https://github.com/Aryan005-ux/ANN-Churn-Classification.git
```

Install dependencies:

```
pip install -r requirements.txt
```

Run the Streamlit app:

```
streamlit run app.py
```

---

## Author

Aryan Gupta
GitHub: https://github.com/Aryan005-ux
