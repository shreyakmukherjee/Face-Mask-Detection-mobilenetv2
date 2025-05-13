# 😷 Face Mask Detection using MobileNetV2

This project demonstrates face mask classification using a pre-trained MobileNetV2 model. It was built using TensorFlow in a Jupyter Notebook environment and is capable of distinguishing between people wearing a mask and those without.

---

## Table of Contents
1. [Project Structure](#project-structure)
2. [Features](#features)
3. [Setup Instructions](#setup-instructions)
    - [Prerequisites](#prerequisites)
    - [Installation](#installation)
4. [Example Usage](#example-usage)
5. [Example Output](#example-output)
    - [Model Accuracy](#model-accuracy)
    - [Sample Predictions](#sample-predictions)
6. [Dataset](#dataset)
7. [Contributing](#contributing)

---

## 📁 Project Structure

- `face_mask_dtector.ipynb`: Jupyter Notebook for training, validating, and testing the MobileNetV2 model.
- `README.md`: Project description and setup guide.
- `requirements.txt`: Python dependencies for the project.
- `model.h5` *(optional)*: Saved model file.
- `images/` *(optional)*: Folder containing input/output images.

---

## ✨ Features

1. **MobileNetV2 Transfer Learning**:
   - Pre-trained on ImageNet, fine-tuned for face mask detection.
   - Efficient and lightweight model architecture.

2. **Binary Classification**:
   - Classes: `Mask` and `No Mask`.
   - Evaluation using accuracy, confusion matrix, and visual outputs.

3. **Notebook-Based Workflow**:
   - Fully executed in Jupyter Notebook or Google Colab.
   - Includes data preprocessing, training, evaluation, and prediction steps.

---

## 🛠️ Setup Instructions

### ✅ Prerequisites

- Python 3.8+
- Git installed
- Jupyter Notebook or Google Colab

### 🧩 Installation

1. Clone the repository:
   ```bash
   git clone https://github.com/<your-username>/face-mask-detection.git
   cd face-mask-detection

2. Install dependencies:
    ```bash
   pip install -r requirements.txt
3. Open the notebook:
   ```bash
   jupyter notebook face_mask_dtector.ipynb
Or upload it to Google Colab and run it there.

---
## ▶️ Example Usage
Run all cells step by step.

Model will train and validate on the face mask dataset.

Visualizations will display training progress and predictions.

---

## 📊 Example Output

### ✅ Model Accuracy
- **Training Accuracy**: ~98%  
- **Validation Accuracy**: ~96%

---

### 🖼️ Sample Predictions
- **Input**: Image of person wearing a mask  
  ➡️ **Predicted Class**: Mask 😷

- **Input**: Image of person without a mask  
  ➡️ **Predicted Class**: No Mask ❌

---

## 📚 Dataset

This project uses the **Face Mask Detection Dataset** from Kaggle:  
🔗 [https://www.kaggle.com/datasets/ashishjangra27/face-mask-detection](https://www.kaggle.com/datasets/omkargurav/face-mask-dataset)

---

## 🤝 Contributing

Feel free to fork this repository, open issues, or submit pull requests to:

- Add real-time webcam detection with OpenCV.
- Deploy the model with Streamlit or Flask.
- Improve accuracy or expand to multiple classes.
