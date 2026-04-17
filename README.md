<<<<<<< HEAD
# Crop Recommendation System
=======
<<<<<<< HEAD
# 🌾 Smart Crop Recommendation System
>>>>>>> e2082d77c72f74ff7bf0954ba76e7f891a72cf0c

![Python](https://img.shields.io/badge/Python-3.9-blue)
![Machine Learning](https://img.shields.io/badge/ML-Scikit--Learn-orange)
![GUI](https://img.shields.io/badge/GUI-CustomTkinter-green)
![Status](https://img.shields.io/badge/Status-Completed-brightgreen)
![License](https://img.shields.io/badge/License-MIT-yellow)

---

## 📌 Overview

The **Smart Crop Recommendation System** is a machine learning application designed to recommend the most suitable crop based on soil and environmental parameters.

This project combines **data science, machine learning, and modern UI design** to deliver an intuitive and interactive user experience.

---

## 🚀 Key Features

* 🌱 Predicts best crop based on soil nutrients
* 🎯 High accuracy (~97%) using Random Forest
* 🎛️ Interactive slider-based input system
* 🌙 Light/Dark mode support
* 🖼️ Displays crop image dynamically
* ⚡ Real-time prediction
* 🧠 Data-driven feature ranges (handled outliers)

---

## 🧠 Machine Learning Models

The following models were implemented and compared:

* Decision Tree
* Naive Bayes
* Support Vector Machine (SVM)
* Logistic Regression
* **Random Forest (Best Performing Model)**

---

## 📊 Input Features

| Feature | Description             |
| ------- | ----------------------- |
| N       | Nitrogen content        |
| P       | Phosphorus content      |
| K       | Potassium content       |
| pH      | Soil pH level           |
| EC      | Electrical Conductivity |
| S       | Sulfur                  |
| Cu      | Copper                  |
| Fe      | Iron                    |
| Mn      | Manganese               |
| Zn      | Zinc                    |
| B       | Boron                   |

---

## 🖥️ GUI Highlights

* Built using **CustomTkinter**
* Modern, responsive layout
* Scrollable slider-based inputs
* Theme-aware UI (Light & Dark mode)
* Clean and user-friendly design

---

## 📸 Application Preview
### GUI Interface
D:\Gihub_projects\CropRecommendation-\images\screenshot 1.png

### Interface after prediction
D:\Gihub_projects\CropRecommendation-\images\screenshot 2.png


---

## 📁 Project Structure

```
crop-recommendation/
│
├── Crop_Recommendation.ipynb
├── Crop.csv
├── README.md
├── requirements.txt
│
├── images/
│   ├── mango.jpg
│   ├── grapes.jpg
│   ├── potato.jpg
│   ├── ragi.jpg
│   ├── mulberry.jpg
│   └── pomegranate.jpg
```

---

## ⚙️ Installation

### 1. Clone Repository

```
git clone https://github.com/your-username/crop-recommendation.git
cd crop-recommendation
```

### 2. Install Dependencies

```
pip install -r requirements.txt
```
---


The target variable is the type of crop which includes:

- Grapes
- Mango
- Mulberry
- Pomegranate
- Potato
- Ragi

## Model Performance

The accuracy of the models is as follows:

| Model                | Accuracy |
|----------------------|----------|
| Decision Tree        | 0.94     |
| Naive Bayes          | 0.97     |
| SVM                  | 0.91     |
| Logistic Regression  | 0.96     |
| Random Forest        | 0.97     |

## Usage

### Predicting Crop

1. **Train the Model**: Train the model using the dataset and the chosen algorithms.
2. **Make Predictions**: Input the soil parameters into the trained model to get the crop recommendation.

### Sample Predictions

```python
# Sample data for prediction
data = np.array([[150,70,217,6,0.6,0.25,10,116,60,55,22]])

# Using Random Forest model for prediction
prediction = RF.predict(data)
print(prediction)  # Output: ['pomegranate']
```

## Conclusion

This Crop Recommendation System leverages machine learning to provide accurate and reliable crop suggestions based on soil properties. The integration of multiple algorithms ensures robustness and high performance, making it a valuable tool for farmers and agronomists.

# Crop-Recomendation-System
The Crop Recommendation System is a machine learning-based application that predicts the most suitable crop to grow based on soil and environmental parameters.
<<<<<<< HEAD
=======
---

## 💡 Key Improvements

* Replaced manual inputs with sliders for better UX
* Handled outliers for realistic predictions
* Integrated image visualization
* Implemented adaptive UI (theme switching)

---

## 🔮 Future Enhancements

* 📊 Feature importance visualization
* 🌐 Deployment with Flask/Streamlit
* 🌍 Weather API integration
* 📱 Mobile application version
* 🤖 AI assistant for farming guidance

---

## 👨‍💻 Author

**Aman Singh**

---

## 📜 License

This project is licensed under the MIT License.

---

## ⭐ If you like this project

Give it a star ⭐ on GitHub!

---

## 🧠 Interview Insight

> Built an end-to-end ML system with an interactive GUI, optimized user input using sliders, handled dataset inconsistencies, and enhanced UX with real-time predictions and visualization.

---


>>>>>>> e2082d77c72f74ff7bf0954ba76e7f891a72cf0c
