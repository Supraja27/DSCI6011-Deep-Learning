# DSCI6011-Deep-Learning
# Cotton Plant Disease Prediction
# Overview:
This project aims to develop a deep learning solution for predicting diseases in cotton plants based on leaf images. The models utilize deep learning architectures, including InceptionV3 and ResNet50, to classify images as healthy or diseased.
# Dataset:
We use a comprehensive examination of a dataset obtained from Kaggle, consisting of images depicting cotton plants categorized into healthy and diseased classes. The dataset was meticulously organized into training, validation, and testing sets to ensure the reliability and effectiveness of our deep learning model. Each image was labeled and divided into four distinct categories: fresh cotton leaf, fresh cotton plant, diseased cotton leaf, and diseased cotton plant.
DatasetLink: https://www.kaggle.com/datasets/janmejaybhoi/cotton-disease-dataset?resource=download 
# Features:
- Utilizes pre-trained deep learning models (InceptionV3 and ResNet50) for image classification.
- Provides accurate predictions of cotton plant diseases based on leaf images.
- Allows users to input images of cotton plant leaves and receive predictions on whether they are healthy or diseased.
# Deep Learning Models:
- ResNet50: Part of the Residual Networks family, this model has 50 layers deep and is known for its ability to train rapidly without degradation in performance, thanks to residual connections.
- InceptionV3: This model is known for its complexity and efficiency, using a mixture of convolutional widths and pooling to improve recognition accuracy at lower computational costs.
# Data Preprocessing: 
Data preprocessing is crucial to adapt raw image data to the input requirements of these models:

- Image Resizing: Images are resized to meet the input size specifications of each model (224x224 for ResNet50 and 299x299 for InceptionV3).
- Normalization: Pixel values are normalized to ensure model stability and improve convergence during training.
- Data Augmentation: Techniques like rotation, shifting, and flipping are used to artificially expand the training dataset, which helps improve model generalization.
# Evaluation Metrics:
Throughout the training process, we meticulously monitored our model's performance using a diverse array of evaluation metrics. These metrics, including accuracy, precision, recall, and F1-score, provided valuable insights into the model's effectiveness in accurately classifying cotton plant diseases. By closely analyzing these metrics, we were able to refine our approach and improve model performance iteratively.
- Saved Models Link: https://drive.google.com/drive/folders/1_Z4TCqedTgptnKRPc0UgCmwT63W__MEr?usp=sharing
# Results and Analysis:
Our efforts culminated in a comprehensive analysis of the training results, shedding light on the model's behavior and performance trends. We presented training and validation loss/accuracy curves, providing valuable insights into the model's convergence and potential issues such as overfitting or underfitting. Additionally, we delved into the model's performance on the test dataset, offering valuable insights for future iterations and improvements.
# Conclusion:
In conclusion, our exploration into cotton disease classification using deep learning represents a significant step forward in leveraging AI technologies for agricultural applications. By harnessing the power of deep learning, we can revolutionize crop management practices, leading to increased productivity, sustainability, and resilience in agriculture. Thank you for joining us on this journey, and we look forward to continuing to push the boundaries of innovation in agriculture

