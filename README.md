# Ensemble Model for Lung Disease Detection using Multimodal-Images and Breathe Easy Website
![GitHub Logo](https://github.com/samyukth7/Ensamble-Model-for-Lung-Disease-Detection-using-Multimodal-Images/blob/main/Images/1st%20page.png)
## Website(GUI)
![GitHub Logo](https://github.com/samyukth7/Ensamble-Model-for-Lung-Disease-Detection-using-Multimodal-Images/blob/main/Images/fine.png)

## Description
 
In this project, we used deep learning methods to classify lung diseases
using the VGG16 and ResNet50 models.The ResNet50 model was trained on a multiclass classification issue with five
classes, the VGG16 model was trained on a binary classification problem
with two classes. Our experimental findings demonstrated the utility of
both models in categorising lung illnesses, with the ResNet50 model performing better than VGG 16
model when it comes to CT images whereas on the other hand  we noted
that the VGG16 model outperformed the Resnet50 model when it comes to Xray images.
Additionally, we implemented both the models in Flask, enabling
us to create a web application for classifying lung diseases. Medical practitioners can submit chest X-ray and CT scan images into this user-friendly
web tool to get instantaneous predictions on the existence of lung disease.

Some of the lung diseases that can be detected are given below:

## Adenocarcinoma
![GitHub Logo](https://github.com/samyukth7/Ensamble-Model-for-Lung-Disease-Detection-using-Multimodal-Images/blob/main/Images/andro.png)


## Large cell carcinoma
![GitHub Logo](https://github.com/samyukth7/Ensamble-Model-for-Lung-Disease-Detection-using-Multimodal-Images/blob/main/Images/lar.png)

## Squamous cell carcinoma
![GitHub Logo](https://github.com/samyukth7/Ensamble-Model-for-Lung-Disease-Detection-using-Multimodal-Images/blob/main/Images/sm.png)

## Pneumonia
![GitHub Logo](https://github.com/samyukth7/Ensamble-Model-for-Lung-Disease-Detection-using-Multimodal-Images/blob/main/Images/pno.png)

## Resnet-50 Architectures
![GitHub Logo](https://github.com/samyukth7/Ensamble-Model-for-Lung-Disease-Detection-using-Multimodal-Images/blob/main/Images/resnet.png)

## VGG-16 Architectures

![GitHub Logo](https://github.com/samyukth7/Ensamble-Model-for-Lung-Disease-Detection-using-Multimodal-Images/blob/main/Images/vgg.png)

## Accuracy  Table
![GitHub Logo](https://github.com/samyukth7/Ensamble-Model-for-Lung-Disease-Detection-using-Multimodal-Images/blob/main/Images/ll.png)


## Features

- Image upload functionality
- Prediction using two different models
- User-friendly web interface

## Technologies Used

- Python
- Flask
- TensorFlow
- Keras
- Bootstrap (for the frontend)
- jQuery (for handling asynchronous requests)

## Models

1. **Model 1**: ResNet50-based model for detecting pneumonia in CT scans.
2. **Model 2**: VGG16-based model for detecting pneumonia in X-ray images.

## Getting Started

1. Clone the repository.
2. Install the required dependencies using `pip install -r requirements.txt`.
3. Run the Flask app using `python app.py`.
4. Open the web application in your browser.

## Usage

1. Access the home page and navigate to the 'Upload Report' section.
2. Choose an image file (.png, .jpg, .jpeg) for prediction.
3. Click the 'Detect' button to get predictions from both models.
4. View the results displayed on the web page.


## Acknowledgments

- Include credits or acknowledgments if needed.# Ensamble-Model-for-Lung-Disease-Detection-using-Multimodal-Images
