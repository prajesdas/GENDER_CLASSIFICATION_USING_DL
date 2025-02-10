# 👩‍💻 GENDER CLASSIFICATION USING DEEP LEARNING

## 📌 Overview
This project implements gender classification using deep learning techniques. It leverages convolutional neural networks (CNNs) to predict gender based on facial images and count the number of people present in a given situation.

## 🚀 Features
- 🧠 Deep learning-based gender classification
- 🎭 Uses OpenCV for face detection
- 🔢 Counts the number of people in an image or video
- 🏗️ Pre-trained models for efficient predictions
- 📊 Supports real-time and batch processing

## 📂 Project Structure
```
📁 GENDER_CLASSIFICATION_USING_DL
├── 📜 GENDER CLASSIFICATION.ipynb  # Jupyter Notebook for model training & testing
├── 📜 README.md                     # Project documentation
├── 📜 age_deploy.prototxt           # Model configuration file
├── 📜 haarcascade_frontalface_default.xml # Haar Cascade for face detection
```

## 🛠️ Requirements
Ensure you have the following dependencies installed:
```bash
pip install tensorflow keras opencv-python numpy matplotlib
```

## 🎯 Usage
Run the Jupyter notebook to train and test the model:
```bash
jupyter notebook GENDER_CLASSIFICATION.ipynb
```
For real-time detection using a webcam:
```python
python real_time_gender_classification.py
```

## 📸 Sample Output
The model predicts gender as either **Male** or **Female** and counts the number of people present based on input images or video feeds.

## 🙌 Contributing
Feel free to submit issues or pull requests to improve the project!

## 📜 License
This project is licensed under the MIT License.


