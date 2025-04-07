# Cataract-detection-Using-Tensorflow

Cataract Detection Using TensorFlow
A deep learning-based project focused on early cataract detection through image classification, built using TensorFlow and real-world medical datasets.

Overview
Cataracts remain a leading cause of preventable blindness worldwide, particularly in regions where access to timely medical care is limited. This project presents an AI-driven approach to detect cataracts from retinal images, aiming to assist in early diagnosis and improve screening efficiency.

The model is trained on the Cataract Image Dataset from Kaggle (https://www.kaggle.com/datasets/nandanp6/cataract-image-dataset), which contains labeled images of eyes with and without cataracts. The primary goal is to build a reliable and interpretable binary classification model that can distinguish between healthy and cataract-affected eyes with high accuracy.

Project Highlights


- Uses TensorFlow and Keras to implement both custom CNNs and pre-trained architectures such as EfficientNet.

- Incorporates standard preprocessing techniques like resizing, normalization, histogram equalization, and data augmentation to improve model generalization.

- Achieves high classification performance with a focus on recall and precision, ensuring reliability in clinical-like settings.

- Includes Grad-CAM visualizations for interpretability, showing which regions of the eye influenced the model’s predictions.

- Designed with deployment in mind, supporting model export for TensorFlow Lite and ONNX.

Motivation
The project addresses the need for accessible, affordable diagnostic tools in ophthalmology. By combining open-source tools and publicly available datasets, it demonstrates how machine learning can be applied to real medical challenges, particularly for underserved populations.

Future Work

1. Optimization for mobile and edge deployment

2. Expansion to multi-disease detection (e.g., diabetic retinopathy, glaucoma)

3. Integration into a prototype mobile app or web-based screening tool

