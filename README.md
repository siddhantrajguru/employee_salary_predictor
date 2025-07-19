
---

```markdown```
# 💼 Employee Salary Predictor

Welcome to the **Employee Salary Predictor** — a Streamlit-powered web app that estimates an employee's annual salary based on several key factors like age, gender, education, job title, and experience.

🔗 **Live Demo**: [Try the App](https://employe-salary-prediction.streamlit.app/)



## 📌 Features

- 🧠 **Machine Learning Model**: Trained using **Linear Regression**
- 📋 **User Inputs**: Age, Gender, Education, Job Title, Experience
- 💹 **Outputs**: Salary prediction in **USD** and **INR**
- 📈 **Model Performance**: Displays **R² score** and evaluation chart
- 🎨 **Styled UI**: Custom CSS for clean, dark-themed interface

---

## 🖥️ Tech Stack

| Tool        | Description                        |
|-------------|------------------------------------|
| Python 🐍   | Core programming language          |
| Streamlit 🌐| Web interface framework            |
| Scikit-learn 📊 | Machine learning library       |
| Pandas & NumPy 📦 | Data processing & arrays     |
| Joblib 📁   | Model persistence and loading      |
| Matplotlib & Seaborn 📉 | Data visualization     |

---

## 📂 Project Structure

```

├── app.py                   # Streamlit app
├── salary\_predictor.pkl     # Trained ML model
├── evaluation\_plot.png      # Model evaluation plot
├── model\_score.txt          # R² score of the model
├── requirements.txt         # List of Python dependencies
└── README.md                # Project documentation

````

---

## 🚀 How to Run Locally

1. 📥 Clone the repository:
   ```bash
   git clone https://github.com/siddhantrajguru/employee_salary_predictor.git
   cd employee_salary_predictor
````

2. 🧱 Create and activate a virtual environment:

   ```bash
   python -m venv venv
   source venv/bin/activate   # On Windows: venv\Scripts\activate
   ```

3. 📦 Install dependencies:

   ```bash
   pip install -r requirements.txt
   ```

4. ▶️ Launch the app:

   ```bash
   streamlit run app.py
   ```

---

## 📊 Sample Prediction

| Input               | Value           |
| ------------------- | --------------- |
| Age                 | 30              |
| Gender              | Female          |
| Education Level     | Master's Degree |
| Job Title           | Data Scientist  |
| Years of Experience | 5               |

🔮 **Predicted Salary**: \$85,000 (USD) / ₹7,05,500 (INR)


---

## 🙌 Acknowledgements

* 💻 Inspired by Kaggle datasets & ML tutorials
* 🛠 Built with [Streamlit](https://streamlit.io)
* 📈 Model trained with `scikit-learn`

---

## 🤝 Contributing

Pull requests are welcome! For major changes, please open an issue first to discuss what you would like to change.

---



