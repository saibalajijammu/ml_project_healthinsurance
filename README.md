# 🏥 Health Insurance Premium Predictor


A machine learning web application that predicts **health insurance premium costs** based on personal and demographic information. Built with Python and deployed using Streamlit.

---

## 🚀 Live Demo

👉 **[Try the App Here](https://mlprojecthealthinsurance.streamlit.app/)** 

---

## 📌 Overview

This project uses supervised machine learning to estimate health insurance charges for individuals. Users can input their personal details and instantly receive a predicted insurance cost. The app compares predictions from multiple ML models, with the best-performing model serving the final output.

---

## 🧠 ML Models Used

| Model | Description |
|---|---|
| **Linear Regression** | Baseline model to capture linear relationships |
| **Random Forest** | Ensemble tree-based model for better accuracy |
| **XGBoost** | Gradient boosting model for highest performance |

> The best-performing model (based on R² and RMSE) is used for final predictions.

---


## ⚙️ How to Run Locally

### 1. Clone the repository
```bash
git clone https://github.com/saibalajijammu/ml_project_healthinsurance.git
cd ml_project_healthinsurance
```

### 2. Install dependencies
```bash
pip install -r requirements.txt
```

### 3. Run the Streamlit app
```bash
streamlit run app.py
```





## 🛠️ Tech Stack

- **Language:** Python
- **ML Libraries:** Scikit-learn, XGBoost
- **Data Processing:** Pandas, NumPy
- **Visualization:** Matplotlib, Seaborn
- **Web App:** Streamlit
- **Model Serialization:** Joblib 

---

## 🤝 Contributing

Contributions are welcome! Feel free to open an issue or submit a pull request.

---

## 📄 License

This project is licensed under the [MIT License](LICENSE).

---


> ⭐ If you found this project helpful, please give it a star!
