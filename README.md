# 🎭 Deepfake Detection using CNN–RNN Ensemble

This project detects AI-generated deepfake videos using a hybrid CNN–RNN architecture that learns both **spatial (frame-level)** and **temporal (motion-level)** patterns.

---

## 🧠 Features
- **CNN (ResNet50/Xception)** for frame-level feature extraction  
- **RNN (LSTM/GRU)** for temporal motion analysis  
- **Ensemble learning** to boost accuracy and reduce false positives  
- **Streamlit web app** for real-time demo  

---

## 📁 Folder Structure

deepfake-detection/
├── data/               # dataset (not uploaded)
├── models/             # trained models
├── notebooks/          # experiments and notebooks
├── src/                # source code
│   ├── data_preprocessing.py
│   ├── cnn_model.py
│   ├── rnn_model.py
│   ├── ensemble_model.py
│   └── app.py
├── README.md
├── requirements.txt
└── .gitignore
