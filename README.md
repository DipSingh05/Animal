# Wildlife Classification & Detection Using AI/ML

  This project aims to use articial intelligence and machine learning for wildlife
  species classication and detection using image recognition and deep learning
  models

## How does a Convolutional Neural Network function ?  

[deep.ai](https://deepai.org/machine-learning-glossary-and-terms/convolutional-neural-network): CNNs process images as volumes, receiving a color image as a rectangular box where the width and height are measure by the number of pixels associated with each dimension, and the depth is three layers deep for each color (RGB). These layers are called channels. Within each pixel of the image, the intensity of the R, G, or B is expressed by a number. That number is part of three, stacked two-dimensional matrices that make up the image volume and form the initial data that is fed to into the convolutional network. The network then begins to filter the image by grouping squares of pixels together and looking for patterns, performing what is known as a convolution. This process of pattern analysis is the foundation of CNN functions.<br><br>


![CNN](https://miro.medium.com/max/2510/1*vkQ0hXDaQv57sALXAJquxA.jpeg)


### Libraries
  - numpy (Linear Algebra)
  - pandas (Data Manipulation and Analysis)
  - glob (File Manipulation)
  - os (File Manipulation)
  - regex (text patterns)
  - random (sampling data)
  - PIL (image processing) 
  - Sklearn (Evaluation Metrics)
  - Pytorch (Deep Learning)


### The Road Ahead

  We break the notebook into separate steps.  Feel free to use the links below to navigate the notebook.
  
  * [Step 1](#step1): Import Libraries and Load the Dataset 
  * [Step 2](#step2): Create a CNN to Classify Wild Animals (from Scratch)
  * [Step 3](#step3): Create a CNN to Classify Wild Animals (using Transfer Learning) 
  * [Step 4](#step3): Test the model and create an Algorithm
  
  We first mount the folder on the google drive with the dataset.

### License

  -MIT License
