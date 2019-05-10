# Faster-R-CNN by Keras
## Introduction
The original code of Keras version of Faster R-CNN I used was written by RockyXu66 (resource link: https://github.com/RockyXu66/Faster_RCNN_for_Open_Images_Dataset_Keras .) I have tried to predict 10 classes, namely, hallway, human, magazine, cards, signs, laptop, dustbins, cookingpans, fire extinguisher, refrigerator. I have trained the model with 7114 ground truths.

## Project Structure:

data_preparation.ipynb is for creating the annotation files for training and testing.

data_prep_if_needed.ipynb is for separating images to their corresponding folders based on the groung truth data.

frcnn_train_vgg.ipynb is the file to train the model. The configuration and model saved path are inside this file.

frcnn_test_vgg.ipynb is the file to test the model with test images and calculate the mAP (mean average precision) for the model. 
output_file_generation_FCNN is to create .txt files having the information of predicted output by FCRNN for every class indivisually.

plot_iou.ipynb is to claculate accuracy, precision, recall and f1 score.

## Result for some test images
<p float="left">
    <img src="screenshots/2.jpg" width="425"/> 
    <img src="screenshots/3.jpg" width="425"/>
</p>
<p>
    <img src="screenshots/4.jpg" width="425"/> 
    <img src="screenshots/5.jpg" width="425"/> 
</p>

