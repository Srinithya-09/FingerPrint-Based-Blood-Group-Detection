# FingerPrint-Based-Blood-Group-Detection

This project implements a deep learning-based system to predict an individual's blood group from fingerprint images. The system uses CNN and RNN architectures to analyze ridge patterns and temporal features for accurate classification.

---

## 🎯 Objective

To develop an intelligent system that can classify blood groups (A, B, AB, O) by analyzing fingerprint patterns, aiding in quick and non-invasive medical identification.

---

## 🧠 Key Features

- **CNN** for spatial feature extraction from fingerprint ridges
- **RNN** for modeling temporal ridge flow dependencies
- Image preprocessing for ridge enhancement and noise removal
- Blood group classification into categories: A, B, AB, O (+/-)
- Real-time prediction and accuracy optimization

---

## 🗂️ Project Structure

Fingerprint-BloodGroup-Detection/
│
├── dataset/
│ ├── A/
│ ├── B/
│ ├── AB/
│ └── O/
│
├── models/
│ └── fingerprint_blood_model.h5
│
├── preprocessing/
│ └── enhance_fingerprint.py
│
├── main.py
├── utils.py
├── requirements.txt
└── README.md
## 🔧 How to Run

1. **Clone the Repository*
   git clone https://github.com/your-username/fingerprint-bloodgroup.git
   cd fingerprint-bloodgroup
   
3. **Install Dependencies**
pip install -r requirements.txt

4. **Run the Main Script**
python main.py

**📈 Technologies Used Python**

TensorFlow / Keras

OpenCV

CNN (Convolutional Neural Networks)

RNN (Recurrent Neural Networks)

NumPy, Pandas, Matplotlib

**📊 Results (Example)**
Metric	Value
Accuracy	88.6%
Precision	87.2%
Recall	89.5%
F1-Score	88.3%


**🧪 Sample Workflow**
Input: Fingerprint image

Preprocessing: Enhance ridges, remove noise

Feature Extraction: CNN + RNN

Output: Predicted Blood Group (e.g., B+)


👩‍💻 Author
Saindla Srinithya – Final Year CSE (AIML)
Email: [srinithyasridhar@gmail.com]

📜 License
This project is licensed under the MIT License - see the LICENSE file for details.
