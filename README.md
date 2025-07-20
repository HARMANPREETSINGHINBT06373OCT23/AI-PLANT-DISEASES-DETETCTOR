# 🌿 Plant Disease Detector (Streamlit App)

A simple deep learning-powered web application for detecting common plant diseases in **tomato, potato, and corn** leaves. Built with **PyTorch**, **Streamlit**, and a custom `TinyCNN` model, this project serves as a **learning tool** to explore image classification, model deployment, and UI integration using Streamlit.

---

## 🚀 Live Demo

> ⚠️ *This app is a learning project and not intended for professional or agricultural diagnostic use.*

🌐 Try the app (if deployed on Streamlit Cloud or Vercel):  
**[Click here to open](https://your-deployment-url.streamlit.app)**

---

## 🧠 Features

- Upload images of plant leaves to detect diseases
- Predicts among **10 plant disease categories**
- Uses a minimal **Convolutional Neural Network (CNN)** for demonstration
- Friendly UI with **Streamlit**
- Real-time classification using PyTorch
- Definitions and health status for each prediction

---

## 🖼️ Supported Classes

| Plant   | Disease/Class                |
|---------|------------------------------|
| Tomato  | Bacterial Spot, Early Blight, Leaf Mold, Septoria Spot, Yellow Leaf Curl, Healthy |
| Potato  | Early Blight, Late Blight, Healthy |
| Corn    | Common Rust |

---

## 📦 Installation

1. **Clone this repository**:

```bash
git clone https://github.com/yourusername/plant-disease-detector.git
cd plant-disease-detector
Create a virtual environment (optional but recommended):

bash
Copy
Edit
python -m venv venv
source venv/bin/activate  # or venv\Scripts\activate on Windows
Install dependencies:

bash
Copy
Edit
pip install -r requirements.txt
🧪 Run the App Locally
bash
Copy
Edit
streamlit run app.py
Then open http://localhost:8501 in your browser.

🛠 Tech Stack
Python 3.8+

PyTorch

Streamlit

Torchvision

Pillow

⚠️ Disclaimer
This app is not a professional medical or agricultural tool. It is built purely for educational purposes and may produce incorrect or misleading results.
Please consult expert sources or agricultural professionals for accurate diagnoses and recommendations.

📁 Project Structure
bash
Copy
Edit
├── app.py                  # Streamlit app entry point
├── model/                  # (Optional) Folder for saved model weights
├── requirements.txt        # Python dependencies
└── README.md               # Project documentation
❗ Usage Restriction
This project is intended only for personal learning and experimentation.
