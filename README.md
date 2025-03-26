# Project Name : Melanoma Detection Using Custom CNN
> This project aims to develop a custom Convolutional Neural Network (CNN) model to detect melanoma, a deadly form of skin cancer, from images of skin lesions. The model is trained on a dataset containing images of various skin cancer types, including melanoma, and is designed to assist dermatologists by automating the detection process. By leveraging deep learning techniques and image classification, this model helps in early diagnosis, potentially reducing manual efforts and enhancing diagnostic accuracy.


## Table of Contents
* [General Info](#general-information)
* [Technologies Used](#technologies-used)
* [Conclusions](#conclusions)
* [Acknowledgements](#acknowledgements)


## General Information
- Background: Melanoma is one of the deadliest forms of skin cancer. Early detection can significantly improve the chances of survival, which is why an automated system to detect melanoma can be beneficial for   dermatologists. This project aims to build a custom Convolutional Neural Network (CNN) model for melanoma detection from skin lesion images.

- Business Problem: The business problem this project addresses is the need for efficient tools to assist dermatologists in detecting melanoma early. Manual evaluation of skin lesions is time-consuming, and an automated system can help speed up the diagnosis process, reducing errors and workload.

- Dataset: The dataset used in this project is from the ISIC (International Skin Imaging Collaboration) archive, which contains 2357 images of various skin cancer types, including melanoma.
  The dataset is split into 9 categories:
  Actinic keratosis, Basal cell carcinoma, Dermatofibroma, Melanoma, Nevus, Pigmented benign keratosis, Seborrheic keratosis, Squamous cell carcinoma, Vascular lesion

  The images were split into training and testing directories, with data augmentation applied to improve the model's performance and reduce overfitting.



## Conclusions
- The custom CNN model shows promising results, with accuracy gradually increasing through training. However, we observed some overfitting, which was addressed with data augmentation techniques.
- After applying augmentation, the model's performance improved, particularly in its ability to generalize across different types of skin lesions.
- Handling class imbalances with the Augmentor library significantly improved model robustness, especially for underrepresented classes.
- The model's final validation accuracy and loss show satisfactory results, indicating its potential for real-world deployment in aiding melanoma detection.


## Technologies Used
- TensorFlow (2.x) - version 2.15.0
- Matplotlib - version 3.8.0
- Numpy - version 1.26.4
- Pandas - version 2.2.2
- PIL (Python Imaging Library) - version 11.0.0
- Augmentor - version 0.2.12


## Acknowledgements
- This project was inspired by Upgrad IIIT Bangalore PG program on ML and AI.
- This project was based on Convolutional Neural Networks Tutorial of this course.


## Contact
Created by [@ritesh4aiml] - feel free to contact me!
