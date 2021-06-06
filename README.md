# Key Facial Point Detection 
_A Deep learning and CNN (Convolutional Neural Network) project_

"Facial keypoint detection is a challenging problem in the field of computer vision. It serves as the basis for Emotional AI. The keypoint detection is done by predicting the coordinates of certain facial features." In this paper, facial keypoint detection is predicted using convolutional neural networks.

## Summary

* The Model achieved an accuracy of 70% which can be increased if we decrease the batch size and increase the iterations.
* Originally, the dataset had few images so data Augmentation has been used to increase the dataset. 
* Data augmentation involves increasing and decreasing the brightness, zooming in of the images,flipping around vertical axis. 
* The Model struggles to provide accurate results on the side face.

This project has five main components: 

* Data Visualization 
* Data Augmentation 
* Building Deep Residual Neural Network 
* Compile and Train Model
* Model performance Evaluation, all focused on data from [(via Kaggle)](https://www.kaggle.com/c/facial-keypoints-detection).  

The Data set consists of x and y coordinates of 15 facial key points. Input images are gray scale with 96x96 pixels. RESNET (Residual Network) will be used as  it skip connection feature which provides training of 152 layers without vanishing gradient issues. It works by joining Identity mapping on top of CNN. 

Files in this repo:
* **Keypoint_code.ipynb**: a Jupyter Notebook containing project code.

The Resnet portion of this project was inspired by [Coursera](https://www.coursera.org/learn/facial-key-point-detection/) Course.
