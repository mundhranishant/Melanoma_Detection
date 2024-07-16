
# Melanoma Detection
> A Convolutional Neural Network (CNN) based model to accurately detect melanoma, a type of skin cancer. Early detection of melanoma is crucial as it accounts for 75% of skin cancer deaths. This project aims to assist dermatologists by evaluating images and alerting them about the presence of melanoma, thereby reducing manual effort in diagnosis.

## Table of Contents
* [General Info](#general-information)
* [Technologies Used](#technologies-used)
* [Conclusions](#conclusions)
* [Acknowledgements](#acknowledgements)
* [Contact](#contact)

## General Information
- **Project Background**: Melanoma is a deadly type of skin cancer if not detected early. This project builds a CNN-based model to help in early detection by evaluating skin lesion images.
- **Business Problem**: Automating the detection of melanoma can significantly reduce the workload of dermatologists and increase the accuracy of early diagnosis, potentially saving lives.
- **Dataset Used**: The dataset consists of images categorized into nine classes: Actinic keratosis, Basal cell carcinoma, Dermatofibroma, Melanoma, Nevus, Pigmented benign keratosis, Seborrheic keratosis, Squamous cell carcinoma, and Vascular lesion. The training dataset has 2239 images, and the testing dataset has 118 images.

### **Important Note**
**Dataset Locations**: The locations of the datasets in the code are specific to the author's environment. To execute the code in your own environment, please update the dataset paths as per your convenience. 
- Training dataset path: `/content/drive/MyDrive/Dataset/Train`
- Testing dataset path: `/content/drive/MyDrive/Dataset/Test`
- Augmented dataset path: `/content/drive/MyDrive/Dataset/AugmentedDataset`

You can change these paths in the following sections of the code:

# Defining the path for train and test images
data_dir_train = `/content/drive/MyDrive/Dataset/Train`
data_dir_test = `/content/drive/MyDrive/Dataset/Test`
augmented_data_dir = `/content/drive/MyDrive/Dataset/AugmentedDataset`

## Conclusions
- **Conclusion 1**: The initial basic model showed significant overfitting, with training accuracy much higher than test accuracy.
- **Conclusion 2**: Data augmentation and regularization improved the model's performance and generalization, but overfitting persisted.
- **Conclusion 3**: Further improvements with balanced data and class weighting showed better generalization but still had room for improvement.
- **Conclusion 4**: Although improvements were observed, the test accuracies indicated that more advanced techniques and further tuning are required for optimal performance.

## Technologies Used
- **Python** - version 3.10
- **TensorFlow** - version 2.x
- **Keras** - version 2.4
- **Matplotlib** - version 3.4
- **Pandas** - version 1.3
- **NumPy** - version 1.21
- **Augmentor** - version 0.2.12

## Acknowledgements
- This project was inspired by the need for early detection of melanoma to save lives.
- References: The project used the TensorFlow and Keras libraries for building and training the CNN models.
- This project was based on various tutorials and documentation available on the TensorFlow and Keras websites.

## Contact
Created by [@mundhranishant] - feel free to contact me!
