# Image-Quality-Detection

Image quality detection has always been a rather difficult problem to solve in computer vision.Image blur detection can be done using various techniques. Some of the most effecient approaches are:
<b>
  
1. Variation of the Laplacian

2. Convolutional Neural Networks (CNN)

</b>

These classifiers can be used to predict whether a given image is blurred or clear.

# Required Libraries:

The libraries required along with thier version are mentioned below:
* Python  (3.7)
* Keras   (2.3.1)
* OpenCV  (4.2.0)
* NumPy   (1.18.5)
* Pandas  (1.0.5)
* Matplotlib (3.2.2)
* scikit-learn (0.23.1)
* Pickle

# Dataset used:

The dataset used in this repository is <b>CERTH Image Blur Dataset</b>. 
Link to download the dataset: 

```http://mklab.iti.gr/files/imageblur/CERTH_ImageBlurDataset.zip```

# 1. Variation of the Laplacian

In order to run this code

Step 1: Open Laplacian-Method-Evaluation.ipynb in your Jupyter Notebook

Step 2: Click on the Run button.

The test accuracies after execution are:

<b>
  
* DigitalBlurSet : 98.12 %
  
* NaturalBlurSet : 71.20 %

</b>

# 2. Convolutional Neural Networks (CNN)

In order to run this code

Step 1: Open CNN-Model-Evaluation.ipynb in your Jupyter Notebook

Step 2: Click on the Run button.

The test accuracies after execution are:

<b>
  
* DigitalBlurSet : 93.75 %
  
* NaturalBlurSet : 41.10 %

</b>

# References

https://www.pyimagesearch.com/2015/09/07/blur-detection-with-opencv/
