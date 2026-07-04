# PCOS Detection System

A Python-based desktop application for **early detection of Polycystic Ovary Syndrome (PCOS)** using **Machine Learning** and **Tkinter GUI**. The system analyzes patient medical data, predicts the likelihood of PCOS, and also provides precautionary guidance for awareness and management.

---

## 📌 Project Overview

Technology is transforming healthcare by making disease analysis and prediction faster, more accessible, and data-driven. **Polycystic Ovary Syndrome (PCOS)** is one of the most common hormonal disorders affecting women globally, and early detection is important for timely treatment and lifestyle management.

This project focuses on building a **PCOS Detection System** using **Python**, **Tkinter**, and **Machine Learning**. The application allows users to interact through a graphical interface, perform PCOS prediction based on medical data, and view precaution-related guidance.

---

## 🎯 Objectives

- Develop a machine learning-based system for **PCOS prediction**
- Provide a **simple GUI-based application** for user interaction
- Support **early detection and awareness** of PCOS
- Display **prediction results** in an easy-to-understand format
- Provide **basic precautionary guidance** related to PCOS

---

## ✨ Features

- User-friendly **Tkinter GUI**
- Login, registration, and forgot password modules
- Data preprocessing and model training workflow
- PCOS prediction using trained ML model
- Display of model accuracy and output results
- Precaution / awareness section for PCOS management

---

## 🛠️ Technologies Used

- **Python**
- **Tkinter** – GUI development
- **Pandas** – data handling
- **NumPy** – numerical operations
- **Scikit-learn** – machine learning model building
- **Matplotlib** – visualization / performance display
- **SQLite** – login and user data storage
- **Joblib** – model saving/loading
- **Pillow** – image handling

---

## 📂 Project Structure

```bash
PCOS-Detection-System/
│── gui main.py
│── GUI_Main_and_train.py
│── Check_Prediction.py
│── pcos precaution.py
│── login.py
│── registration.py
│── forgot password.py
│── PCOS_infertility.csv
│── new.joblib
│── dataset link.txt
│── accuracy.PNG
│── output.PNG
│── output1.PNG
│── loss.png
│── assets/
│   ├── background and GUI images
│── README.md
│── requirements.txt
│── .gitignore


⚙️ How It Works
The dataset is loaded and cleaned.
Required preprocessing steps are applied.
A machine learning model is trained on PCOS-related medical attributes.
The trained model is saved using Joblib.
Through the GUI, users can enter or test data for prediction.
The system predicts whether the patient is likely to have PCOS.
The application also includes a precaution section for awareness and basic guidance.
📊 Machine Learning Workflow
Dataset loading
Missing value handling
Label encoding / preprocessing
Train-test split
Model training
Accuracy evaluation
Prediction on user input
🖥️ Modules Included
1. Main GUI

The starting interface of the project that connects the user to the system.

2. Login / Registration

Allows users to create an account, log in, and manage credentials.

3. Model Training

Handles data preprocessing, training, and performance evaluation of the machine learning model.

4. PCOS Prediction

Allows prediction of PCOS based on medical input values.

5. Precaution Module

Displays basic precautionary and awareness-related guidance for PCOS.

📈 Output

The system provides:

PCOS prediction result
Accuracy / performance output
Precaution-related information
GUI-based interaction for easy use
🚀 How to Run the Project
1. Clone the repository
git clone https://github.com/your-username/PCOS-Detection-System.git
cd PCOS-Detection-System
2. Install required libraries
pip install -r requirements.txt
3. Run the main file
python "gui main.py"

If you rename the file to gui_main.py, then run:

python gui_main.py
📦 Requirements

Install the following Python libraries before running the project:

pandas
numpy
matplotlib
pillow
scikit-learn
joblib
opencv-python
📸 Screenshots
Main Screen

Accuracy Output

Prediction Output

📚 Dataset

The dataset used in this project contains PCOS-related patient medical parameters for prediction and analysis.

Dataset source:

Kaggle PCOS dataset
Dataset link included in the project files (dataset link.txt)
🔮 Future Enhancements
Improve model accuracy with advanced ML algorithms
Add more medical parameters and real-time analysis
Build a web-based or mobile-based version
Add better report generation and data visualization
Enhance UI design and user experience

👩‍💻 Author

Shreya
