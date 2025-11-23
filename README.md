<h2>🚦 Indian Traffic Sign Classification using CNN</h2>


This project focuses on classifying Indian traffic signs using a Convolutional Neural Network (CNN).
A total of 13,971 images across 58 classes were preprocessed, augmented, and trained to build a robust deep-learning model capable of accurately identifying traffic signals from real-world images.
The workflow includes data loading, augmentation, model building, training, evaluation, and prediction.

<h4>📂 Dataset</h4>

**Kaggle Dataset:**
🔗 https://www.kaggle.com/datasets/neelpratiksha/indian-traffic-sign-dataset

**🔧 Technologies Used**
  - Python
  - TensorFlow / Keras
  - OpenCV
  - NumPy / Pandas
  - Matplotlib

<h4>📌 Features</h4>
  1) Loaded 13,971 images (58 classes) using ImageDataGenerator
  2) Applied data augmentation: rotation, zoom, shifts
  3) Built CNN model for multi-class classification
  4) Achieved strong accuracy with stable learning curves
  5) Ready for further deployment (Flask/Streamlit)

**▶️ How to Run**
[pip install -r requirements.txt]
python train.py

📈 Model Output

Training & Validation accuracy graphs

Confusion matrix

Final test performance

Predictions for new images

🛠 Future Improvements

Use Transfer Learning (VGG16 / ResNet / MobileNet)

Deploy as a web app

Add real-time camera predictions
