
# Pneumonia Detection System 🫁🧠

A web-based application that detects pneumonia from chest X-ray images using a deep learning model. The project combines a ReactJS frontend with a FastAPI backend integrated with a trained CNN model.

## 🚀 Live Demo

👉 [Check out the live app here](https://pneumoniadetectionsystem.netlify.app/)

---

## 🧩 Features

- Upload chest X-ray images for real-time prediction
- Deep learning model trained on medical image datasets
- Clean, responsive UI for a smooth user experience
- Fast inference through optimized backend API
- Deployed and accessible through a public demo link

---

## 🛠️ Tech Stack

### 🔹 Frontend
- ReactJS
- HTML5, CSS3
- Netlify (for deployment)

### 🔹 Backend
- FastAPI (Python)
- Uvicorn (ASGI server)
- Trained CNN model using TensorFlow/Keras
- Image preprocessing with OpenCV & PIL

### 🔹 Model
- Convolutional Neural Network (CNN)
- Trained on a labeled dataset of chest X-rays
- Binary classification: Pneumonia vs Normal

---

## 📂 Project Structure

```
/frontend            --> ReactJS app for UI
/backend             --> FastAPI backend with prediction logic
/model               --> Trained deep learning model (.h5 or .pt)
/notebooks           --> Training and evaluation Jupyter notebooks
```

---

## 📸 Screenshots

*Add some screenshots of your app interface or prediction results here.*

---

## 🔄 How It Works

1. User uploads a chest X-ray image via the web interface.
2. Image is sent to the FastAPI backend.
3. The backend processes the image and feeds it into the trained CNN model.
4. Prediction result is returned to the frontend and displayed.

---

## 📊 Model Performance

- Accuracy: 90% 
- Dataset: Pneumonia detection Dataset Kaggle Chest X-Ray Images (Pneumonia).
- Metrics: Accuracy, Precision, Recall.

---

## 📦 Installation & Local Setup

### 1. Clone the Repository

```bash
git clone https://github.com/your-username/pneumonia-detection-app.git
cd pneumonia-detection-app
```

### 2. Set up Backend

```bash
cd backend
pip install -r requirements.txt
uvicorn main:app --reload
```

### 3. Run Frontend

```bash
cd frontend
npm install
npm start
```

---

## 🧠 Future Improvements

- Add support for multi-class classification (e.g., bacterial vs viral pneumonia)
- Improve model performance with more data and augmentation
- Add user authentication and history tracking
- Integrate Grad-CAM or heatmap for explainable AI

---

## 🙌 Credits

- Dataset: [Kaggle – Chest X-Ray Images (Pneumonia)](https://www.kaggle.com/datasets/paultimothymooney/chest-xray-pneumonia)
- Frameworks: TensorFlow, React, FastAPI

