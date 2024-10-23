# Project Name
> Outline a brief description of your project.


## Table of Contents
* [General Info](#general-information)
* [Technologies Used](#technologies-used)
* [Conclusions](#conclusions)
* [Acknowledgements](#acknowledgements)

<!-- You can include any other section that is pertinent to your problem -->

## General Information
- The project is about creating a CNN model for classifying the skin cancer based n imput image.
- The training dataset contains 2357 images labeling each into 9 different type of skin cancer
- The goal is to create a CNN model which can detect the class of an incoming image as a specific type of cancer with some accuracy.
- The dataset consists of 2357 images of malignant and benign oncological diseases, which were formed from the International Skin Imaging Collaboration (ISIC). All images were sorted according to the classification taken with ISIC, and all subsets were divided into the same number of images, with the exception of melanomas and moles, whose images are slightly dominant



## Conclusions
- The CNN model overfits without dropout and gives around 50% accuracy
- The overfitting problem is reduced a bit using data augmentation startegy where the images are randomly augmented
- Class imbalance is one of the major issue as few class types have more images than others.The accuracy improved considerably once the class imbalance is removed
- Accuracy on validation data is around 85%.




## Technologies Used
- Python
- Tensorflow
- Keras



## Contact
Created by [@MT2012039] - feel free to contact me!


<!-- Optional -->
<!-- ## License -->
<!-- This project is open source and available under the [... License](). -->

<!-- You don't have to include all sections - just the one's relevant to your project -->
