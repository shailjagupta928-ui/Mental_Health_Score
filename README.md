<img width="1852" height="798" alt="Screenshot (102)" src="https://github.com/user-attachments/assets/afdd5b7f-5f7e-47c3-a0e7-b55d0872f3be" />
<img width="1706" height="853" alt="Screenshot (101)" src="https://github.com/user-attachments/assets/42bbee83-849c-4154-9e7d-d20cf416e8bc" />
# 🧠 Mental Health Scorer | Student Wellness Analytics

A machine learning-based web application that predicts a student's mental health score based on their daily habits, social media usage, academic routine, lifestyle, and perceived stress levels.

The project aims to explore how digital behavior and lifestyle patterns can influence student well-being through data-driven insights.

> **Disclaimer:** This application provides a model-based prediction for educational and analytical purposes only. It is not a medical diagnosis or a substitute for professional mental health advice.

## ✨ Features

- **Interactive User Interface:** Clean, modern, and responsive interface built using HTML, CSS, and JavaScript.
- **Student Profile:** Collects age, gender, country, and academic information.
- **Digital Habits Analysis:** Considers social media usage, screen time, and daily phone unlocks.
- **Lifestyle & Stress Analysis:** Takes study hours, physical activity, sleep duration, and perceived stress into account.
- **ML-Based Prediction:** Generates a predicted mental health score on a scale of 0–10.
- **Visual Score Dashboard:** Displays the prediction using a graphical gauge and signal strength indicator.
- **User-Friendly Experience:** Allows users to submit their information and generate another prediction.

## 🛠️ Tech Stack

| Technology | Purpose |
|---|---|
| HTML5 | Frontend structure |
| CSS3 | Styling, layouts and responsive design |
| JavaScript | Form handling and frontend interactions |
| Python | Machine learning and backend logic |
| FastAPI | Backend API |
| Scikit-learn | Machine learning model |
| Pandas & NumPy | Data processing |
| Joblib / Pickle | Model serialization |

## ⚙️ How It Works

1. The user enters personal and academic information.
2. The application collects digital habits and lifestyle details.
3. Input data is processed and passed to the trained machine learning model.
4. The model generates a predicted mental health score.
5. The result is displayed through an interactive dashboard.

## 📊 Input Parameters

- Age
- Gender
- Country
- Academic Level
- Most-used Social Media Platform
- Daily Screen Time
- Daily Phone Unlocks
- Study Hours
- Physical Activity
- Sleep Duration
- Perceived Stress Level

## 📁 Project Structure

```text
Mental-Health-Scorer/
│
├── index.html
├── style.css
├── script.js
├── main.py
├── ML_Project.ipynb
│
├── Mental_Health_Model.pkl
├── Mental_Health_Scores.pkl
│
├── requirements.txt
├── README.md
└── Student Social Media And Mental Health Impact.csv
```

## 🚀 Installation & Setup

**1. Clone the repository**

```bash
git clone YOUR_GITHUB_REPOSITORY_URL
```

**2. Navigate to the project folder**

```bash
cd Mental-Health-Scorer
```

**3. Install dependencies**

```bash
pip install -r requirements.txt
```

**4. Run the application**

```bash
uvicorn main:app --reload
```

**5. Open in your browser**

```text
http://127.0.0.1:8000
```

*Note: The backend should serve the frontend files and expose the prediction API.*

## 🎯 Project Objective

The primary objective is to understand the relationship between students' digital habits, academic routines, lifestyle choices, and mental well-being using machine learning.

This project combines frontend development, backend integration, and machine learning to build an interactive student wellness analytics application.

## 🔮 Future Improvements

- Add more detailed wellness insights.
- Improve prediction accuracy through model optimization.
- Introduce interactive data visualizations.
- Add personalized lifestyle recommendations.
- Improve mobile responsiveness.
- Deploy the application online.

## 👩‍💻 Author

**Shailja Gupta**

BCA Student | Aspiring AI/ML Engineer

GitHub: [shailjagupta928-ui](https://github.com/shailjagupta928-ui)

---

⭐ If you find this project interesting, consider giving the repository a star!
