# Deepfake Detection System 🎭🔍

A powerful AI/ML-based Deepfake Detection System designed to identify manipulated face-swap videos using deep learning. This project is built using a ResNeXt + LSTM architecture for video classification and is integrated with a Node.js backend for real-time inference and deployment.

## 💡 Overview

With the rise of AI-generated media, especially face-swapped deepfake videos, ensuring digital media authenticity has become crucial. Our system aims to detect such videos and flag manipulated content using advanced video processing techniques and deep learning.

---

## 🚀 Features

- 🔎 **Deepfake Video Classification** (Real vs Fake)
- 🧠 **ResNeXt + LSTM** model architecture
- 🧪 Trained on public deepfake datasets
- 🖥️ **Node.js API** for fast and scalable backend
- 📦 Easy-to-use web interface (optional UI)
- 🎥 Supports real-time video file analysis

---

## 🧠 Model Architecture

- **ResNeXt-50**: Feature extraction from video frames
- **LSTM**: Temporal analysis of frame sequences
- **Sigmoid Output**: Binary classification (Real / Fake)

---

## 🗃️ Dataset

The model is trained on benchmark Deepfake datasets such as:

- [DFDC](https://www.kaggle.com/c/deepfake-detection-challenge)
- [FaceForensics++](https://github.com/ondyari/FaceForensics)

---

## 🛠️ Tech Stack

| Component     | Technology            |
| ------------- | --------------------- |
| Backend       | Node.js, Express.js   |
| Model         | PyTorch / TensorFlow  |
| Video Processing | OpenCV, FFmpeg     |
| Deployment    | VS Code               |
| ML Libraries  | NumPy, Pandas, etc.   |

---

## 📦 Installation

### Prerequisites
- Python 3.8+
- Node.js 14+
- `ffmpeg` installed
- GPU (recommended)

### Clone the repository

```bash
git clone https://github.com/your-username/deepfake-detection.git
cd deepfake-detection
```

### Python Backend (Model)

```bash
cd backend
pip install -r requirements.txt
python detect.py
```

### Node.js Server

```bash
cd server
npm install
node app.js
```

---

## 📤 API Usage

### POST `/api/detect`

**Payload:**

- FormData with video file

**Response:**

```json
{
  "prediction": "fake",
  "confidence": 0.94
}
```

---

## 📈 Project Highlights

- ✅ Successfully detects deepfake face-swaps in video
- ⏱️ Real-time or near real-time processing
- 🛡️ Supports secure API endpoints
- 🌐 Easily pluggable to front-end web or mobile apps

---

## 🔒 Future Scope

- Real-time webcam deepfake detection
- Explainable AI (XAI) integration
- Lighter model for mobile deployment
- Integration into social media platforms

---

## 🙋‍♂️ Author

**Choudhury Prasad Khadiratna**  
B.Tech CSE, GIET University  
Aspiring Machine Learning Engineer  
Projects: SAR Image Colorization, Real-Time Face Recognition, Deepfake Detection  
GitHub: [your-link-here]

---

## 📄 License

This project is open source and available under the [MIT License](LICENSE).
