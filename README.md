# 📩 Spam Detection Project

A Machine Learning project that classifies SMS messages as **Spam** or **Ham (Not Spam)** using Natural Language Processing (NLP).

---

## 📌 Project Description

Spam messages are a common problem in digital communication.  
This project builds a text classification model that automatically detects whether a message is spam or not.

The model is trained on a labeled SMS dataset and uses text vectorization techniques to convert text into numerical features before applying a machine learning algorithm.

---

## 🎯 Objectives

- Clean and preprocess text data
- Perform exploratory data analysis (EDA)
- Convert text into numerical format using vectorization
- Train a classification model
- Evaluate model performance
- Save the trained model for future predictions

---

## 📂 Project Structure
```
Spam-Detection/
│
├── Spam_Detection.ipynb   # Main notebook (training + evaluation)
├── spam.csv               # Dataset
├── requirements.txt       # Required libraries
├── README.md              # Project documentation
└── .gitignore             # Ignored files
```


---

## ⚠️ Important Note About `.pkl` Files

The following files are **NOT included** in this repository:

- `model.pkl`
- `vectorizer.pkl`

These files are generated after training the model.

### To create them:
1. Open `Spam_Detection.ipynb`
2. Run all cells
3. The notebook will automatically save the `.pkl` files

This is standard practice because `.pkl` files are usually large and auto-generated.

---

## 🛠 Technologies Used

- Python
- Pandas
- NumPy
- Scikit-learn
- Matplotlib / Seaborn
- Jupyter Notebook

---

## 🚀 Installation & Usage

### 1️⃣ Clone the Repository
```bash
git clone https://github.com/Kalyan-Burada/spam-mail-detector
cd spam-mail-detector
```

### 2️⃣ Install Required Libraries
```bash
pip install -r requirements.txt
```

### 3️⃣ Run the Notebook
```bash
jupyter notebook
```

Open **Spam_Detection.ipynb** and run all cells.


## 🔍 Model Workflow
Import dataset

Data cleaning and preprocessing

Text vectorization (CountVectorizer / TF-IDF)

Train machine learning model

Evaluate model accuracy

Save model and vectorizer using pickle

📊 Model Output
The model predicts:

✅ Ham (Not Spam)

🚫 Spam

Example:

Input:
"Congratulations! You won a free lottery ticket."

Output:
Spam

## 📈 Future Improvements
Deploy as a web application

Improve accuracy using advanced models

Use Deep Learning (LSTM / Transformers)

Add real-time prediction API

## 👤 Author
Kalyan Burada