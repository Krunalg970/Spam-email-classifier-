# 📧 Spam Email Classifier

A Machine Learning project that classifies emails as **Spam** or **Ham (Not Spam)** using **Logistic Regression** and **Natural Language Processing (NLP)** techniques.

---

## 🚀 Project Overview

This project builds a **Spam Email Detection Model** using Python and Scikit-learn. The model is trained on email text data and predicts whether a message is spam or not.

This project demonstrates:

* Data preprocessing
* Text feature extraction (TF‑IDF)
* Logistic Regression model
* Model evaluation
* Prediction system

---

## 🛠️ Technologies Used

* Python
* NumPy
* Pandas
* Scikit‑learn
* Matplotlib
* Jupyter Notebook

---

## 📂 Project Structure

```
Spam-Email-Classifier/
│
├── spam_email_model.ipynb   # Main notebook
├── mail_data.csv            # Dataset
└── README.md                # Project documentation
```

---

## 📊 Dataset

The dataset contains email messages labeled as:

* **Spam (0)** → Unwanted Emails
* **Ham (1)** → Legitimate Emails

Dataset features:

* Message text
* Label (Spam / Ham)

---

## ⚙️ Installation

Clone the repository:

```bash
git clone https://github.com/your-username/spam-email-classifier.git
```

Navigate to project folder:

```bash
cd spam-email-classifier
```

Install dependencies:

```bash
pip install numpy pandas scikit-learn matplotlib
```

---

## ▶️ How to Run

Open Jupyter Notebook:

```bash
jupyter notebook
```

Open:

```
spam_email_model.ipynb
```

Run all cells.

---

## 🧠 Model Workflow

### 1. Import Dependencies

* NumPy
* Pandas
* Scikit‑learn

### 2. Data Collection & Preprocessing

* Load dataset
* Handle null values
* Label encoding

### 3. Feature Extraction

* Convert text to numerical features using **TF‑IDF Vectorizer**

### 4. Model Training

* Logistic Regression model

### 5. Model Evaluation

* Training Accuracy
* Test Accuracy

### 6. Prediction System

* Input email
* Model predicts spam or ham

---

## 📈 Model Accuracy

* Training Accuracy: ~97% (approx)
* Test Accuracy: ~96% (approx)

*(Accuracy may vary depending on dataset)*

---

## 💡 Example Prediction

```python
input_mail = ["Free entry in 2 a weekly competition to win tickets!!!"]

prediction = model.predict(input_data_features)

if prediction[0] == 0:
    print("Spam Mail")
else:
    print("Ham Mail")
```

---

## 🎯 Features

✅ Spam detection
✅ Machine learning model
✅ Text preprocessing
✅ Logistic Regression
✅ Easy to understand

---

## 📌 Future Improvements

* Add Deep Learning Model
* Create Web App
* Deploy using Streamlit
* Add API support

---

## 🤝 Contributing

Contributions are welcome! Feel free to fork the repository and submit pull requests.

---

## 📜 License

This project is open-source and available under the **MIT License**.

---

⭐ If you like this project, don't forget to give it a star on GitHub!
