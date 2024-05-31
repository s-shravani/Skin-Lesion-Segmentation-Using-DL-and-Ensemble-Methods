SKIN LESION SEGMENTATION USING DEEP LEARNING AND ENSEMBLE TECHNIQUES

--> Overview

1. This project focuses on Skin Lesion Segmentation using Deep Learning techniques
2. Employed Unet, HRnet and Segnet models to achieve high-precision skin lesion segmentation
3. Conducted comprehensive data preprocessing and augmentation to enhance data accuracy and model performance
4. The ensemble technique used in this project is "AVERAGE WEIGHTING".
5. Developed a Graphical User Interface (GUI) for seamless interaction with ensemble-based deep learning models
6. Allows users to easily detect skin lesions  


--> GUI Implementation

In our skin lesion segmentation project, we have developed a graphical user interface (GUI) that facilitates the detection of skin lesion images. Users can upload an image of a skin lesion, and the GUI processes this image to produce a segmented output. The segmented result is designed to highlight areas of concern, if any. Specifically, the GUI provides clear guidance on interpreting the results: a completely white output signifies that no lesion has been detected, implying there is no cause for concern. Conversely, if the segmentation reveals a dark spot, it indicates a potential lesion, and users are advised to consult a medical professional for further evaluation. This user-friendly interface aims to assist in the early detection and management of skin lesions, enhancing the accessibility of dermatological assessments.


--> Datasets used - ISIC 2018 and PH2 

1) https://challenge.isic-archive.com/data/#2018
        
2) https://www.kaggle.com/datasets/athina123/ph2dataset



--> 3 dataset folders were used in this project:

A] dataset folder includes ISIC2018_Task1_Training_GroundTruth and ISIC2018_Task1-2_Validation_Input

B] ph2_resized folder includes trainx and trainy

C] unet_dataset folder includes:
  - ISIC2018_Task1_Test_GroundTruth
  - ISIC2018_Task1_Validation_GroundTruth
  - ISIC2018_Task1-2_Validation_Input
  - ISIC2018_Task1-2_Test_Input
  - ISIC2018_Task3_Training_GroundTruth.csv

The "27-3-2024 UPDATE" folder includes all the files under the hrnet folder on this git repo.

The 'test_images' folder includes images for gui testing


