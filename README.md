Human Scream Detection using Machine Learning

This project detects human screams in audio clips using machine learning techniques. It can be used in security systems or smart surveillance setups to automatically alert authorities when a scream is detected.



scream-detection/
├── Assets/                      # Folder containing audio data
│   ├── positive/                # Audio files with human screams
│   ├── negative/                # Audio files without screams (e.g., background noise, talking)
│   └── testing/                 # Audio files used for testing or recorded clips
│
├── scream_detection.py         # Main Python script for training, prediction, and recording
├── requirements.txt            # List of Python dependencies
├── README.md                   # Project documentation and instructions
├── .gitignore                  # Specifies files/folders to ignore in Git



Features

- Extracts audio features using **Librosa**
- Classifies audio using a **Neural Network** with TensorFlow/Keras
- Real-time **audio recording** and prediction
- Visualizes model accuracy and loss over epochs
- Alerts if scream is detected in audio



Installation

1. **Clone the repository:**
git clone https://github.com/Prathima-B-A/scream-detection.git
cd scream-detection