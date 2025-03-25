Human Scream Detection using Machine Learning

This project detects human screams in audio clips using machine learning techniques. It can be used in security systems or smart surveillance setups to automatically alert authorities when a scream is detected.



Project Structure

scream-detection/ ├── Assets/ │ ├── positive/ # Audio files with human screams │ ├── negative/ # Audio files without screams (background noise, talking, etc.) │ └── testing/ # Test audio files or recorded clips ├── scream_detection.py # Main script with training, prediction, and recording code ├── requirements.txt # List of dependencies ├── README.md # Project documentation ├── .gitignore # Files/folders to ignore in Git └── models/ # Optional folder to save trained models

---

Features

- Extracts audio features using **Librosa**
- Classifies audio using a **Neural Network** with TensorFlow/Keras
- Real-time **audio recording** and prediction
- Visualizes model accuracy and loss over epochs
- Alerts if scream is detected in audio

---

Installation

1. **Clone the repository:**
git clone https://github.com/Prathima-B-A/scream-detection.git
cd scream-detection