# Computer Vision on Vehicle Detection Data

This project is part of the Applied Artificial Intelligence cirriculum through the University of San Diego. It is part of the AAI-521 Computer Vision course. 

--Project Status: Completed

## Installation
This project contains several jupyter notebooks. It is recommended these are run on a computer with high memory and GPU if available as they contain models that are computationally expensive to run. It is also reccommended to leverage cloud resources if available. 
Download one of two notebooks and run them locally with `jupyter notebook <desired_notebook>.ipynb` or download and run in a google colab instance. 

The completed notebooks are: 
- AAI_521_Group5_Final.ipynb (This notebook contains the most well structured data agumentation approaches and final results)
- AAI_521_Group5_Final_CarsDownsampled.ipynb (This model is the same, but includes downsampling of the cars vehicle class)
  
## Project Intro/Objective: 
The goal of this project was to apply computer vision modeling techniques to an image dataset. Using the [vehicle dataset](https://www.kaggle.com/datasets/pkdarabi/vehicle-detection-image-dataset) from Kaggle the aim was to use object detection and classification to create a model that can detect and classify different vehicles on the road. 
Using the YOLOv9 model for its efficiency and high accuracy, this project applies data augmentation, preprocessing and model hyperparameter tuning to achieve strong detection and classification results. This project contains the code to setup and run the R-CNN model in addition to YOLOv9 as a comparison between the two computer vision models on the same dataset. 

## Contributors
- Pawan Tahiliani
- Kim Vierczhalek
- Jory Hamilton

## Methods Used
- YOLO v9
- Faster R-CNN
- Dynamic Augmentation
- Static Augmentation
- Downsampling
- Computer Vision
- Data preprocessing

## Technologies
- Python
- Tensorflow
- Jupyter Notebook
- Google Collab ** (These were all run on google collab)

## Project Description
This project is included as a set of group projects through the University of San Diego. The goal is to build an entire project that solves a real world issue. This specific project has applications outside of the course work as it uses data collected from traffic cameras and can be used in a real world scenario. This project does have a model that preforms with relatively low accuracy and should be tuned and trained on a more robust dataset before attempting to use it in a real-world application.

## Acknowledgments
Thank you to the professors who created a well thought out course with a high level overview of a wide variety of computer vision algorithms, applications and considerations. Special thanks to Siamak Aram for your insightful comments and assisence throughout the course.  
