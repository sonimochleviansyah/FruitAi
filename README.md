# 🍎 FruitVision AI

FruitVision AI is a web-based application for fruit image classification using **Transfer Learning Xception**. The application allows users to upload an image of a fruit and receive the predicted fruit class, confidence score, Top-3 predictions, and inference time through an interactive web interface.

---

## 📌 Features

- 🍎 Fruit Classification
- 🧠 Transfer Learning Xception
- 📷 Image Upload
- 📊 Confidence Score
- 🥇 Top 3 Predictions
- ⚡ Fast Inference Time
- 🌐 Web-based using Flask
- 📱 Responsive Interface

---

## 🗂️ Dataset

**Fruits Classification Dataset**

Classes:

- Apple
- Banana
- Grape
- Mango
- Strawberry

---

## 🧠 Deep Learning Model

- Architecture : Xception
- Method : Transfer Learning
- Framework : TensorFlow & Keras
- Test Accuracy : **91%**

---

## 🛠️ Tech Stack

- Python
- Flask
- TensorFlow
- Keras
- HTML
- CSS
- JavaScript
- Bootstrap 5
- Pillow
- NumPy

---

## 📂 Project Structure

```text
FruitClassificationXception/

│── app.py
│── predict.py
│── train.py
│── class_names.json
│── requirements.txt
│── Procfile
│── runtime.txt
│
├── model/
│     └── best_xception.keras
│
├── templates/
│     ├── base.html
│     ├── index.html
│     ├── result.html
│     └── about.html
│
├── static/
│     ├── style.css
│     └── main.js
│
├── uploads/
│
└── README.md
```

---

## 🚀 Installation

Clone this repository

```bash
git clone https://github.com/USERNAME/FruitVisionAI.git
```

Go to project folder

```bash
cd FruitVisionAI
```

Create Virtual Environment

```bash
python -m venv venv
```

Activate Virtual Environment

Windows

```bash
venv\Scripts\activate
```

Linux / macOS

```bash
source venv/bin/activate
```

Install dependencies

```bash
pip install -r requirements.txt
```

Run application

```bash
python app.py
```

Open browser

```
http://127.0.0.1:5000
```

---

## 🌐 Deployment

The application can be deployed using:

- Railway
- Render
- PythonAnywhere

The trained model is automatically downloaded from Google Drive when the application runs for the first time.

---

## 📸 Application Preview

### Home Page

*(Insert Screenshot Here)*

---

### Prediction Result

*(Insert Screenshot Here)*

---

## 📈 Model Performance

| Metric | Value |
|---------|-------|
| Model | Xception |
| Method | Transfer Learning |
| Test Accuracy | **91%** |
| Classes | 5 |
| Framework | TensorFlow |

---

## 👨‍💻 Author

**Soni Moch Leviansyah**

---

## 📄 License

This project is intended for educational and research purposes.
