
# 🫁 Pneumonia Detection System using Deep Learning

A 🌐 web-based application that detects **pneumonia** from chest X-ray images using a trained deep learning model. Built with **ReactJS** and **FastAPI**, it delivers real-time diagnostic predictions through a clean and responsive UI.

---

## 🚀 Live Demo

🔗 [Click here for the live demo](https://pneumoniadetectionsystem.netlify.app/)

---

## ✨ Features

✅ Upload and scan chest X-ray images  
✅ Instant predictions with confidence score  
✅ Responsive and intuitive user interface  
✅ FastAPI-powered backend with deep learning model  
✅ Deployed and accessible on the web

---

## 🧠 Tech Stack

### 🖥️ Frontend
- ⚛️ ReactJS
- 🎨 HTML5, CSS3
- ☁️ Netlify (deployment)

### 🔧 Backend
- 🐍 FastAPI (Python)
- 🚀 Uvicorn (ASGI server)
- 🧠 CNN model (TensorFlow/Keras)
- 🖼️ OpenCV, PIL for image processing

---

## 🗂️ Project Structure

```
/frontend            --> ReactJS app for user interface
/backend             --> FastAPI backend with ML logic
/model               --> Trained DL model (.h5 / .pt)
/notebooks           --> Training and evaluation notebooks
```

## ⚙️ How It Works

1. 📤 User uploads a chest X-ray image.
2. 🔄 Image is sent to the backend API.
3. 🧠 CNN model analyzes the image.
4. ✅ Prediction is returned and shown on the UI.

---

## 📈 Model Performance

- 🎯 **Accuracy**: 90%  
- 🧪 **Dataset**: Pneumonia Detection Dataset.
- 📊 **Metrics**: Accuracy, Precision, Recall.

---

## 🛠️ Run Locally

### 1️⃣ Clone the Repository

```bash
git clone https://github.com/your-username/pneumonia-detection-app.git
cd pneumonia-detection-app
```

### 2️⃣ Setup Backend

```bash
cd backend
pip install -r requirements.txt
uvicorn main:app --reload
```

### 3️⃣ Run Frontend

```bash
cd frontend
npm install
npm start
```

---

## 🌟 Future Improvements

- 🔍 Add explainability (e.g., Grad-CAM visualization)
- 🧬 Expand to multi-class diagnosis (e.g., bacterial vs viral)
- 🔐 Add user authentication
- 💾 Store user scans and history

---

## 🙏 Credits

- 📚 Dataset: [Kaggle – Chest X-Ray Images (Pneumonia)](https://www.kaggle.com/datasets/paultimothymooney/chest-xray-pneumonia)  
- 🛠️ Tech: TensorFlow, FastAPI, ReactJS
