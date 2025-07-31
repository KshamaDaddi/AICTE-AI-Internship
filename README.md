# 🌿 Smart Irrigation System using Machine Learning

An intelligent irrigation system that uses machine learning to automate water supply decisions based on environmental data like soil moisture, temperature, and humidity. This project helps conserve water and improve crop health by using real-time predictions.

---

## 📌 Project Overview

Agriculture consumes a large portion of freshwater resources. Traditional irrigation methods often lead to overwatering or underwatering, reducing crop productivity. This project uses a **Random Forest Classifier** within a **MultiOutputClassifier** to predict the need for irrigation across multiple crop zones using environmental features.

---

## 🎯 Objectives

- Develop a smart irrigation model using machine learning.
- Automate irrigation decisions based on sensor data.
- Reduce water consumption and maximize efficiency.
- Provide a scalable model for future IoT integration.

---

## 🛠️ Tech Stack & Tools

| Component        | Tool/Library               |
|------------------|----------------------------|
| Programming      | Python 3.x                 |
| Data Handling    | Pandas                     |
| Visualization    | Matplotlib, Seaborn        |
| Machine Learning | Scikit-learn               |
| Model Persistence| Joblib                     |
| Notebook Format  | Jupyter Notebook (`.ipynb`)|

---

## 📁 Repository Structure

```
Smart-Irrigation-System-ML/
│
├── data/
│   └── irrigation_machine.csv         # Dataset
│
├── notebook/
│   └── Smart_Irrigation_System.ipynb  # Complete code notebook
│
├── images/
│   ├── heatmap.png                    # Correlation heatmap
│   ├── model_report.png               # Classification report
│   └── methodology_flowchart.png      # System flowchart
│
├── model/
│   └── irrigation_model.pkl           # Trained model
│
├── README.md                          # Project documentation
└── requirements.txt                   # Python dependencies
```

---

## 🧠 Methodology

```text
[1] Data Acquisition
        ↓
[2] Data Preprocessing (MinMaxScaler)
        ↓
[3] Model Selection (RandomForest + MultiOutputClassifier)
        ↓
[4] Training & Testing (Train-Test Split)
        ↓
[5] Model Evaluation (classification_report)
        ↓
[6] Model Saving (joblib)
        ↓
[7] Future Deployment (IoT + Dashboard)
```



---

## 📊 Dataset Description

The dataset `irrigation_machine.csv` includes:
- 📌 **Features**: Temperature, Humidity, Soil Moisture
- 🎯 **Target Labels**: Whether irrigation is needed for various crops/zones

---

## 📈 Results & Visuals

- ✅ Classification accuracy using `RandomForestClassifier`
- 📊 Heatmap showing feature correlations
- 📋 Evaluation using `classification_report` from Scikit-learn

---

## ▶️ How to Run This Project

1. **Clone the repository**:
```bash
git clone https://github.com/your-username/Smart-Irrigation-System-ML.git
cd Smart-Irrigation-System-ML
```

2. **Install dependencies**:
```bash
pip install -r requirements.txt
```

3. **Launch Jupyter Notebook**:
```bash
jupyter notebook notebook/Smart_Irrigation_System.ipynb
```

4. **Explore model, visuals, and prediction logic**

---

##  `requirements.txt`
pandas
matplotlib
seaborn
scikit-learn
joblib


## 🚀 Future Scope

- Integration with real-time **IoT sensors**
- Automate **water pump control** via Arduino/ESP32
- Web-based dashboard for visualization and control
- Mobile notifications to farmers via IoT cloud platforms


## ✍️ Author

**Kshama Daddi**  
🎓 AI & Data Science Student  
📬 Reach out: [GitHub]https://github.com/KshamaDaddi) • [LinkedIn]https://www.linkedin.com/in/kshamadaddi)


## 📄 License

This project is licensed under the **MIT License** – feel free to use and contribute!


## 🙌 Acknowledgments

- Dataset Reference (if any)
- Academic Mentors
- GitHub Copilot & ChatGPT (for assisted development)


 
