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

## Example  Image
![Screenshot 2024-02-21 230420](https://github.com/ramajaradat/Jordanian-currency-detection/assets/83189283/e35d9427-da60-43dc-ba70-3157b86f4947)

 

### Models Evaluated
The following is best  Roboflow model are evaluated in this project:

## Train
![Screenshot 2024-02-18 220803](https://github.com/ramajaradat/Jordanian-currency-detection/assets/83189283/a47d88ee-89f8-4fb3-a79f-cf1b9c93d47f)

## Test & Valid  
![Screenshot 2024-02-18 220752](https://github.com/ramajaradat/Jordanian-currency-detection/assets/83189283/0e375c09-9072-4dea-8092-36ff09c39420)



## DEmo On Roboflow

Once the model is trained, you can utilize the power of Roboflow for inference on new images of Jordanian currency.Roboflow  provides a user-friendly interface for deploying and utilizing pre-trained models, making it easy to integrate state-of-the-art natural language processing and computer vision capabilities into your projects.

Using the Pre-trained Models
Choose a version : Select a "Best Model"  version wich it the best version we got it.

Input Data: Prepare your input data, in this case, images video ,real time webcam or any link foe image or video  of Jordanian currency, ensuring they are in a compatible format and quality for the chosen model.

Model Inference: Utilize Roboflow  inference capabilities to process the input images through the selected pre-trained model. This step will generate predictions or insights based on the model's understanding of the input data. please follow this Roboflow Demo.[RoboFlow Demo](https://universe.roboflow.com/jordanian-detection/jd-coins-detect/dataset/4)



## Presentation
For more details, please refer to our presentation [presentation](https://prezi.com/p/edit/w9xjp2wqfrti/)

