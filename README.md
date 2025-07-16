# FingerPrint-Based-Blood-Group-Detection

FRACTOSCAN is a deep learning-based system designed to automatically detect bone fractures from X-ray images. The project utilizes Convolutional Neural Networks (CNN) for image classification and includes preprocessing techniques to enhance image quality and model accuracy.

## 🧠 Project Objective

To build an automated tool that can classify X-ray images into **fractured** or **non-fractured** categories by analyzing bone structures using CNN-based image analysis.

## 📂 Project Structure

FRACTOSCAN/
│
├── dataset/
│ ├── train/
│ │ ├── fractured/
│ │ └── non_fractured/
│ └── test/
│ ├── fractured/
│ └── non_fractured/
│
├── models/
│ └── trained_model.h5
│
├── notebooks/
│ └── fracture_detection.ipynb
│
├── utils/
│ └── preprocessing.py
│
├── main.py
├── requirements.txt
└── README.md

## 🔍 Key Features

- Preprocessing using **histogram equalization**, **Gaussian blur**, and **binary thresholding**
- Bone region enhancement using **OpenCV**
- Feature extraction using **CNN (Convolutional Neural Networks)**
- Transfer learning using **ResNet-50**
- Visual explainability using **Grad-CAM**
- Evaluation metrics: Accuracy, Precision, Recall, F1-Score

## 🚀 How to Run

1. **Clone the repository**  
   git clone https://github.com/your-username/fractoscan.git
   cd fractoscan
   
2. **Install dependencies**
pip install -r requirements.txt

3. **Run the main script**
python main.py
