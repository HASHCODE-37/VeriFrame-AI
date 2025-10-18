
# 🕵️‍♂️ Deepfake Detection Web App

A web application that detects deepfake images using a deep learning model trained on the Celeb-DF v2 dataset. Users can upload images to check if they are real or fake.

---

## 🚀 Features

- Upload and analyze images (JPG, PNG, JPEG)
- EfficientNetB4-based deepfake detection
- Real-time prediction results
- Responsive frontend using HTML + CSS (Flask templating)

---

## 🧠 Model Info

- **Model**: EfficientNetB4 (trained on Celeb-DF v2)
- **Accuracy**: ~90%
- **Input Size**: 380x380x3
- **Framework**: TensorFlow / Keras

---

## 📁 Project Structure

```
deepfake-detector/
├── static/
│   ├── css/
│   │   └── style.css
│   └── js/
│       └── script.js
├── templates/
│   └── index.html
├── best_model_b4.h5  # Model file in root directory
├── app.py
└── requirements.txt
```

---

## 💻 Setup Instructions

Language. **Use  Python 3.10**
   ```bash
  [ https://www.python.org/downloads/release/python-3100/]
   ```
1. **Clone the repository**
   ```bash
   git clone https://github.com/your-username/deepfake_webapp.git
   cd deepfake_webapp
   ```
2. **Create Virtual Environment**
   ```bash
   python -m venv venv
   ```
3. **Install dependencies**
   ```bash
   pip install flask tensorflow opencv-python pillow numpy
   ```

4. **Run the application**
   ```bash
   python app.py
   ```

5. **Access the app**  
   Open a browser and go to:  
   [[http://127.0.0.1:5000](http://localhost:5000)]

---

## 👨‍💻 Team – Crew 8 Bits

- Mr. Harsh Mhatre 

**Mentors:**  
- Mrs. Arpita Kante 
- Ms. Aarti Wani 

---

## 🛡️ Disclaimer

This app is for academic and research purposes only. Not intended for commercial or forensic use.

---

## 📬 Contact

For queries, email the contributors directly.
