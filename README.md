📚 AI-powered-loan-Eligibility-Advisor

Loan Prediction System (Flask + Machine Learning + Streamlit)

This project was developed as part of the Infosys Springboard Internship Program.
It is a complete end-to-end Machine Learning application that predicts whether a loan application will be approved based on user input.


---

🚀 Project Overview

The Loan Prediction System is designed to help users understand their chances of getting a loan approved.
It includes:

✔ Machine Learning model (Decision Tree / Logistic Regression)
✔ Flask Web Application
✔ Streamlit Interface (optional chatbot included)
✔ Frontend Pages – Home, About, Chatbot
✔ Model training & prediction
✔ Gemini AI chatbot integration


---

🛠️ Tech Stack Used

Frontend
       =>HTML, CSS
Backend

     =>Python

     =>Flask(optional UI)

      =>Streamlit 


Machine Learning

       =>scikit-learn

      =>NumPy

      =>Pandas

      =>Pickle/Joblib

📂 Project Structure

Main/
│── pycache              # Main Flask application                              # Trained ML model
│── templates/           # HTML templates
│   ├── index.html
│   ├── prediction.html
│── flask_app.py            # CSS, JS, Images
│── Loan Prediction.jpynb          # Chatbot/Streamlit logic (optional)
│── MIT.licence      # Project documentation
│── Project Activity.png     # All dependencies
|-Streamlit_app.py
|-chatbot.by
|-loan.png
|-model.pkl
|_system_architecture.png
|-test.csv
|-train.csv

---

🎯 Features



🤖 Chatbot

Interactive chatbot for collecting user input

Predicts loan approval based on conversation


📊 Loan Prediction

Takes multiple inputs like:

Gender

Married Status

Education

Loan amount

Income


Uses ML model to predict Approved / Not Approved



---

▶️ How to Run the Project Locally

1️⃣ Clone the Repository

git clone https://github.com/Chandrika-sherikar/Infosys-springboard-internship.git
cd Infosys-springboard-internship

2️⃣Install Dependencies

pip install -r requirements.txt


3️⃣   Add Your Gemini API Key
In chatbot.py or chatflask.py :
genai.configure(api_key="YOUR_API_KEY")

4️⃣   Run Streamlit Frontend
streamlit run streamlitapp.py
Runs on → http://localhost:8501

5.Run the Flask App

flask run

or

python app.py

6.Access in Browser

http://127.0.0.1:5000


---

The dependenciesare:

1. Flask
2. scikit-learn
3. numpy
4. pandas
5. Streamlit
6. google-generativeai

📘 Model Training

The ML model was trained using:

DecisionTreeClassifier

Cleaned loan dataset

70–30 train/test split


The trained model is stored in model.pkl for fast prediction.


---

🧪 Future Enhancements

Deploy project on Render / PythonAnywhere

Add admin dashboard

Add user history page

Improve chatbot UI

Add graphs/charts for analytics
