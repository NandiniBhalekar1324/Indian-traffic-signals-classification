<h2>🚦 Indian Traffic Sign Classification using CNN</h2>

<p>
This project focuses on classifying Indian traffic signs using a Convolutional Neural Network (CNN).  
A total of <strong>13,971 images across 58 classes</strong> were preprocessed, augmented, and trained to build a robust deep-learning model capable of identifying traffic signals from real-world images.  
The workflow includes data loading, augmentation, CNN model creation, training, evaluation, and predictions on new images.
</p>

<h3>📂 Dataset</h3>
<p>
<strong>Kaggle Dataset:</strong><br>
🔗 <a href="https://www.kaggle.com/datasets/neelpratiksha/indian-traffic-sign-dataset" target="_blank">
Indian Traffic Sign Dataset
</a>
</p>

<h3>🔧 Technologies Used</h3>
<ul>
  <li>Python</li>
  <li>TensorFlow / Keras</li>
  <li>OpenCV</li>
  <li>NumPy / Pandas</li>
  <li>Matplotlib</li>
</ul>

<h3>📌 Features</h3>
<ul>
  <li>Loaded <strong>13,971 images (58 classes)</strong> using <code>ImageDataGenerator</code></li>
  <li>Applied extensive data augmentation (rotation, zoom, shift)</li>
  <li>Built a CNN model for multi-class traffic sign classification</li>
  <li>Achieved strong accuracy with stable training and validation curves</li>
  <li>Model ready for deployment via Flask or Streamlit</li>
</ul>

<h3>▶️ How to Run</h3>
<pre>
pip install -r requirements.txt
python train.py
</pre>

<h3>📈 Model Output</h3>
<ul>
  <li>Training & validation accuracy / loss curves</li>
  <li>Confusion matrix for class-wise performance</li>
  <li>Final test accuracy</li>
  <li>Predictions on new unseen images</li>
</ul>

<h3>🛠 Future Improvements</h3>
<ul>
  <li>Use Transfer Learning (VGG16 / ResNet50 / MobileNet)</li>
  <li>Deploy as a web application</li>
  <li>Add real-time camera-based predictions</li>
</ul>
