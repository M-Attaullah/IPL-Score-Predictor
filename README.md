# 🏏 IPL Score Predictor

## 🚀 Project Overview
The **IPL Score Predictor** is an AI-powered system designed to predict the total score of a team in an IPL match. It analyzes match details such as venue, batting/bowling teams, striker, and bowler. Built using deep learning, this model leverages a neural network for accurate predictions and provides a user-friendly interface for real-time forecasting.

---

## 🌟 Features

### 🔹 **Data Preprocessing**
- Cleaned historical IPL match data.
- Handled missing values and encoded categorical variables.
- Scaled numerical features using `MinMaxScaler`.

### 🔸 **Model Training**
- Designed a **Neural Network** with multiple dense layers.
- Used **ReLU activation**, **Huber Loss**, and **Adam Optimizer**.
- Tuned hyperparameters for optimal performance.

### 🔹 **Interactive Prediction Tool**
- Built a live prediction interface using `ipywidgets`.
- Users can input match details (venue, teams, players) and get real-time score predictions.

### 🔸 **Model Evaluation**
- **Mean Absolute Error (MAE):** 11.71  
- **Mean Squared Error (MSE):** 330.16  
- **R² Score:** 60.8%  

---

## 🏗️ System Architecture

### 💻 **Model Workflow**
1. **Data Exploration:** Analyzed IPL datasets for feature engineering.  
2. **Preprocessing:** Label encoding, scaling, and train-test splitting.  
3. **Training:** Developed and fine-tuned the neural network.  
4. **Deployment:** Integrated the model into an interactive tool.  

### 🔧 **AI Techniques**
- **Deep Learning:** Dense layers with dropout for regularization.  
- **Loss Function:** Huber Loss to handle outliers.  
- **Optimization:** Adam for efficient convergence.  

### 🛠 **Tech Stack & Tools**
| **Category**       | **Technologies Used**                          |
|--------------------|-----------------------------------------------|
| **Programming**    | Python                                        |
| **Libraries**      | Pandas, NumPy, Scikit-learn, TensorFlow/Keras |
| **UI**             | ipywidgets                                    |
| **Platform**       | Google Colab, VS Code                         |

---

## 🔥 Challenges Overcome
- **Accuracy Improvement:** Achieved a balance between bias and variance through hyperparameter tuning.  
- **Real-Time Prediction:** Seamlessly connected the trained model to an interactive UI for dynamic inputs.  

---

## 📈 Roadmap & Future Scope
- **🌍 Multi-League Support:** Extend predictions to PSL, BBL, etc.  
- **🌦️ Context-Aware Features:** Incorporate weather/pitch conditions.  
- **📱 Responsive UI:** Develop a web/mobile app for broader accessibility.  

---

## 👨‍💻 Team Members
| **Role**               | **Contributions**                              |
|------------------------|-----------------------------------------------|
| **M Attaullah (Lead)** | Designed NN, led project, evaluated metrics.  |
| **M Haris Nisar**      | Data collection, preprocessing, and EDA.      |
| **Abdul Rehman**       | Model training, tuning, and testing.          |
| **M Muqaddas Ali**     | Developed interactive prediction interface.   |

---

## 🤝 Get in Touch!
Passionate about AI, cricket, and problem-solving? Let’s collaborate!  

[![GitHub](https://img.shields.io/badge/GitHub-000?logo=github&logoColor=white)](https://github.com/M-Attaullah) [**M-Attaullah**](https://github.com/M-Attaullah)  

[![LinkedIn](https://img.shields.io/badge/LinkedIn-0077B5?logo=linkedin&logoColor=white)](https://www.linkedin.com/in/muhammad-attaullah-705764333/) [**Muhammad Attaullah**](https://www.linkedin.com/in/muhammad-attaullah-705764333/)  

