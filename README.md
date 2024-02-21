# Jordanian-currency-detection

## Overview 
In this project, we leverage the power of Roboflow tools to create a sophisticated system for detecting and totaling Jordanian currency. Roboflow's comprehensive suite of computer vision solutions streamlines our workflow, allowing us to seamlessly preprocess and augment our currency images for optimal model training. Through the integration of state-of-the-art object detection models, trained on a curated dataset of Jordanian banknotes, Roboflow empowers our system to accurately identify and locate currency within images. The OCR capabilities provided by Roboflow further enhance our ability to recognize denomination values, ensuring precise and efficient currency value extraction. The user-friendly interface of Roboflow facilitates the seamless integration of our solution, allowing users to easily visualize and comprehend the detected banknotes along with their corresponding total value. With Roboflow's tools, we aim to deliver a robust and reliable system for Jordanian currency detection, promising efficiency and accuracy in applications such as financial transactions and currency counting.








## Dataset:
The dataset for this project was created by collecting images of Jordanian currency  from various website sources. 

### Data Collection:

The dataset consists of images with the following 9 classes:

- 5 Piastres  
- 10 Piastres 
- 25 Piastres 
- 50 Piastres 
- 1 dinar 
- 5 dinar 
- 10 dinar 
- 20 dinar 
- 50 dinar 
<img src="C:\Users\user\Pictures\Screenshots\Screenshot 2024-02-21 230420.png" alt="Example  Image 1"/>
 

### Models Evaluated
The following pre-trained models are evaluated in this project:
- **InceptionV3**
  <div style="display: flex; flex-direction: column; justify-content: space-between;">
  <img src="results/InceptionV3.png" alt="result  Image 1" width="900"/>
  <img src="results/InceptionV3_Con.Matrix.png" alt="result Image 1" width="450" height="300"/>
  <img src="results/InceptionV3_classification report.png" alt="result Image 1" width="450" height="300"/>
  </div>

- **EfficientNet**
   <div style="display: flex; flex-direction: column; justify-content: space-between;">
   <img src="results/efficientNet.png" alt="result Image 2" width="900" height="250"/>
  <img src="results/efficient_Confusion Matrix.png" alt="result Image 2" width="450" height="300"/>
  <img src="results/efficient_classification report.png" alt="result Image 2" width="450" height="300"/>
  </div>
- **ResNet**
   <div style="display: flex; flex-direction: column; justify-content: space-between;">
   <img src="results/ResNet50.png" alt="result  Image 1" width="900" height="250"/>
  <img src="results/ResNet50_Confusion_Matrix.png" alt="result  Image 2" width="450" height="300"/>
  <img src="results/ResNet50_classification_report.png" alt="result  Image 3" width="450" height="300"/>
  </div>
- **VGGNet**
   <div style="display: flex; flex-direction: column; justify-content: space-between;">
   <img src="results/VGG16.png" alt="result  Image 1" width="900" height="300"/>
  <img src="results/VGG16_Con_Matrix.png" alt="result  Image 2" width="450" height="300"/>
  <img src="results/VGG16_Classification_report.png" alt="result  Image 3" width="450" height="300"/>
  </div>

## Inference with Hugging Face

Once the model is trained, you can utilize the power of Hugging Face for inference on new images of Jordanian archaeological sites. Hugging Face provides a user-friendly interface for deploying and utilizing pre-trained models, making it easy to integrate state-of-the-art natural language processing and computer vision capabilities into your projects.

### Using the Pre-trained Models

1. **Choose a Model**: Select a pre-trained model suitable for your task. Hugging Face offers a wide range of models fine-tuned on various datasets, including computer vision models for image classification, object detection, and more.

2. **Input Data**: Prepare your input data, in this case, images of Jordanian archaeological sites, ensuring they are in a compatible format and quality for the chosen model.

3. **Model Inference**: Utilize Hugging Face's inference capabilities to process the input images through the selected pre-trained model. This step will generate predictions or insights based on the model's understanding of the input data.
please follow this <a href="https://huggingface.co/spaces/trs/Image_Classification_with_pre-traind_Models">HuggingFace Demo</a>.
 <img src="example/Image Classification for Archaeological Sites Interface.png" alt="Image Classification for Archaeological Sites Interface" />


## Presentation
For more details, please refer to our presentation <a href="https://prezi.com/p/edit/rob86aji2seu/">here</a>

