# 🧑‍💻 HowOld.AI - AI-Powered Age Prediction 🚀

## 📌 Overview
Welcome to **HowOld.AI**, an AI-powered web app that predicts the age of individuals from images using **Deep Learning**! 🧠📷 
Our application runs **two powerful models** – a **Custom CNN** and a **fine-tuned ResNet18**, and provides accurate predictions directly in the browser. Built with **React + TailwindCSS** on the frontend and **FastAPI** on the backend, this project is optimized for performance and seamless user experience. 🏆

## 🎯 Features
✅ Upload images from your local storage 📂<br>
✅ Predict age using both **Custom CNN** & **ResNet18** models 🧑‍🏫<br>
✅ Compare predictions from both models 📊<br>
✅ GPU-accelerated inference using **PyTorch + Colab** ⚡<br>
✅ Responsive & modern UI built with **React + TailwindCSS** 🎨<br>
✅ Fast and scalable backend powered by **FastAPI** 🚀<br>
✅ Docker support for easy deployment 🐳<br>

---

## 🏗️ Project Directory Structure

```
age-prediction-app/
├── backend/
│   ├── app/
│   │   ├── __init__.py
│   │   ├── main.py              # FastAPI application entry point
│   │   ├── models/
│   │   │   ├── __init__.py
│   │   │   ├── model_loader.py  # Model loading utilities
│   │   │   ├── custom_cnn.py    # Custom CNN definition
│   │   │   └── resnet_model.py  # ResNet model definition
│   │   └── utils/
│   │       ├── __init__.py
│   │       └── image_processing.py # Image preprocessing
│   ├── weights/
│   │   ├── CustomCNN_best_model.pth
│   │   └── ResNet_best_model.pth
│   ├── requirements.txt
│   └── Dockerfile
└── frontend/
    ├── public/
    │   ├── index.html
    │   ├── favicon.ico
    │   └── robots.txt
    ├── src/
    │   ├── App.js
    │   ├── index.js
    │   ├── components/
    │   │   ├── Header.js
    │   │   ├── Footer.js
    │   │   ├── ImageUploader.js
    │   │   ├── Predictions.js
    │   │   └── LoadingSpinner.js
    │   ├── styles/
    │   │   └── index.css
    │   └── assets/
    │       └── sample.jpg
    ├── package.json
    ├── tailwind.config.js
    ├── postcss.config.js
    └── Dockerfile
```

---

## ⚙️ Tech Stack
### 🖥️ Backend (FastAPI)
- FastAPI ⚡ - High-performance API framework
- PyTorch 🧠 - Deep Learning framework
- OpenCV 🎥 - Image processing
- TQDM ⏳ - Progress bar for training
- Docker 🐳 - Containerization

### 🎨 Frontend (React + TailwindCSS)
- React.js ⚛️ - Modern frontend framework
- TailwindCSS 🎨 - Utility-first styling
- Axios 🔄 - API requests
- Framer Motion 🎭 - Animations

---

## 🏃‍♂️ Quickstart Guide

### 1️⃣ Clone the repository
```sh
git clone https://github.com/yourusername/HowOld.AI.git
cd HowOld.AI
```

### 2️⃣ Setup Backend
```sh
cd backend
pip install -r requirements.txt
python3 app/main.py
```
The FastAPI server will start on `http://127.0.0.1:8000` 🚀

### 3️⃣ Setup Frontend
```sh
cd frontend
npm install
npm run dev
```
The React frontend will be available at `http://localhost:5173` 🎨

---

## 🏆 Model Training & Performance
### 🏋️‍♂️ Training Process
We trained two models for age prediction:
1️⃣ **Custom CNN** - A convolutional neural network built from scratch 🛠️
2️⃣ **ResNet18** - A pretrained model with a modified final layer 🎯

### 🔬 Evaluation
| Model         | MSE Loss |
|--------------|----------|
| Custom CNN  |  **X.XX** |
| ResNet18    |  **X.XX** |

💡 **Which model performs better?** 🧐 The pretrained **ResNet18** achieves lower MSE due to transfer learning from large-scale datasets. However, the **Custom CNN** provides insights into training from scratch! 🎓

---

## 🚀 Future Enhancements
✅ Improve UI/UX for better user experience 🎨<br>
✅ Optimize inference speed with ONNX Runtime ⚡<br>
✅ Add support for more advanced models like EfficientNet 🏆<br>
✅ Deploy using **Docker + Kubernetes** ☸️<br>

---

## 🤝 Contributing
We welcome contributions! 🔥 Feel free to **fork** the repository and submit a **pull request**. 🚀

---

## 💌 Connect with Me
📧 Email: mayankmittal29042004@gmail.com.com  
🐙 GitHub: [https://github.com/mayankmittal29/](https://github.com/yourgithub)  

---

## 📜 License
📝 MIT License - Use freely, contribute, and improve! 🎉

