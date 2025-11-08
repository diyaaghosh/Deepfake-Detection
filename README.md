#  Deepfake Detection using CNN

This project detects **deepfake images** (AI-generated vs real faces) using a **Convolutional Neural Network (CNN)** built with **TensorFlow and Keras**.  
The model is trained on a dataset of real and fake images, achieving strong accuracy in distinguishing between them.

---

##  Project Structure

```bash
Deepfake-Detection/
│
├── dataset/
│ ├── train/
│ │ ├── real/
│ │ └── fake/
│ └── test/
│ ├── real/
│ └── fake/
│
├── model/
│ └── deepfake_detection_model.pkl # saved trained model
│
├── deepfake_prediction.ipynb  # main training script
├── requirements.txt # dependencies
└── README.md # project documentation
```

---

##  Setup Instructions

### 1️ Clone the repository
```bash
git clone https://github.com/diyaaghosh/Deepfake Detection.git
cd Deepfake-Detection
```
