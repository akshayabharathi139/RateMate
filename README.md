# RateMate

# 🍽️ Restaurant Aggregate Rating Prediction App

This project predicts the **aggregate rating** of a restaurant based on various features such as delivery options, cuisine, votes, and more. The application is built using **Python**, **Streamlit**, and **Scikit-learn**, and can be deployed locally or on cloud platforms like Streamlit Cloud or Heroku.

---

## 🚀 Features

- Predicts the **aggregate rating** of a restaurant
- User-friendly **web interface** using Streamlit
- Supports multiple cuisines with **multi-label encoding**
- Trained using a cleaned dataset of restaurants and their attributes

---

## 🧠 Tech Stack

- Python 🐍
- Streamlit 🌐
- Scikit-learn 🧠
- Pandas & NumPy 📊
- Joblib 🔧

---

## 📁 Project Structure

RateMate/
│
├── app.py # Streamlit web application
├── train_model.py # Script to train and save the model
├── model.pkl # Trained machine learning model
├── mlb.pkl # MultiLabelBinarizer for cuisines
├── dataset_columns.pkl # Column order used for prediction
├── requirements.txt # Python dependencies
└── README.md # Project documentation




---

## 📊 Input Features

- Has Table Booking (Yes/No)
- Has Online Delivery (Yes/No)
- Is Delivering Now (Yes/No)
- Switch to Order Menu (Yes/No)
- Number of Votes
- Country Code
- Currency
- Rating Color
- Rating Text
- Cuisines (Multi-select)

---

## ✅ Installation & Setup

### 1. Clone the Repository

```bash
git clone https://github.com/yourusername/restaurant-rating-predictor.git
cd restaurant-rating-predictor






3. Create and Activate Virtual Environment (Optional)
python -m venv venv
venv\Scripts\activate    # For Windows
source venv/bin/activate # For Mac/Linux



4. Train the Model (Optional)

python train_model.py


5.Run the Streamlit App
streamlit run app.py




