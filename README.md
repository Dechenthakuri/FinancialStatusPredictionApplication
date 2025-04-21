# 💸 Financial Risk Prediction using Random Forest

This project is a **machine learning-based financial risk prediction system** built using Java. It uses a Random Forest algorithm to predict whether a user is at financial risk based on inputs such as income, credit score, debt-to-income ratio, and more. The system also suggests a **"role model"**—a financially stable individual with similar traits—for those identified as at risk.

---

## 🚀 Features

- 📊 **Predicts financial risk** using Random Forest classifier
- 🧠 Implements **bootstrapping** and **bagging** for training stability
- 🔍 Identifies a **role model** from low-risk profiles
- 💬 Provides personalized suggestions for high-risk users
- 🖥️ Built with Java and JavaFX for a clean, intuitive UI
- 📁 Data sourced from Kaggle for training and testing

---

## 🧩 Technologies Used

| Purpose                | Tool/Library                      |
|------------------------|-----------------------------------|
| Programming Language   | Java (JDK 22)                     |
| IDE                    | IntelliJ IDEA (Community Edition) |
| UI                     | JavaFX                            |
| Machine Learning       | Smile / Weka / custom implementation |
| Version Control        | Git + GitHub                      |

---

## 🧪 Input Fields (UI Form)

The application collects the following information:

- `Income` (Integer)
- `Credit Score` (Integer, 0–850)
- `Debt-to-Income Ratio` (Float)
- `Employment Status` (Employed, Self-employed, Unemployed)
- `Education Level` (PhD, Master's, Bachelor's, High School)
- `Marital Status` (Married, Single, Widowed)

---

## 📁 Project Structure

📦financial-risk-project 
┣ 📂src ┃ 
┣ 📂com.example.financialrisk 
  ┣ 📜HelloApplication.java  
  ┗ 📜RandomForestModel.java 
  ┣ 📜README.md 
  ┣ 📜data.csv 
  ┣ 📜requirements.txt 
  ┗ 📜.gitignore
---

## 📊 How It Works

1. **User inputs** data into the form.
2. Data is passed to the backend where:
   - Bootstrapping and bagging create multiple datasets.
   - A Random Forest model is trained.
   - Predictions are made based on input.
3. If the prediction shows **"at-risk"**, the model:
   - Searches the dataset for **non-risk profiles** similar to the user.
   - Selects one as a **role model**.
   - Displays **personalized suggestions**.

---

## 🧠 AI Setup in IntelliJ

- Install **AI Coding Assistant** plugin via IntelliJ settings.
- Add your OpenAI API key under **Tools > AI Coding Assistant > Settings**.
- You can now generate code suggestions and completions with AI assistance!

---

## ✅ How to Run

1. Clone the repo:
   ```bash
   git clone https://github.com/your-username/financial-risk-project.git

