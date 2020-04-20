# Portfolio
This repository contains a subset of the projects I've been working on. 
The content will be continuously updated since I am improving the existing projects and adding new ones.
The aim of this repository is to show my knowledge to people interested.

## Visual:
* **Face Recognition:** FaceNet, Multi-Task Cascaded Convolutional Neural Network and a linear SVC with Kearas
* **Neuro Style Transfer:** Generating Images based VGG19 implementing Style and Content Loss from intermediate layers and training using  Tensorflow 2.x Graph mode
* **YOLOv2_Object_Detection:** Application of YOLOv2 Object Detection algorithm in Tensorflow 2.x with weights pretrained on the COCO-Dataset. The algorithm performs pretty well in detecting and recognizing the 80 classes. It could be extended to work on custom classes and to work on video. The work uses the work of Allan Zelender and Andrew Ng (Coursera course), however extends them by applying Tensorflow 2.x with some minor additions. 
* **Recognizing Blood Cells disorders:** An exercise of implementing several different CNN type of blocks/layers including: ResNet blocks, Inception blocks, One-to-One convolutions. Additionally, partial reuse of pretrained weights on ResNet50 and Inception with self-training of part of the network with early stopping.
* **Decets Detection and Localization:** Solution for the or the [Severstal: Steel Defect Detection Competition](https://www.kaggle.com/c/severstal-steel-defect-detection). The goal is to precisly localize multiple different type of deffects on an image from produced sheet steel. A U-Net Segmentation with a ResNet34 Backbone and pretrained weights on Imagenet have been used.  
* **Image Segmentation with U-Net:** Implementation of U-Net with MobileNetV2 as encoder and simple Upsampling as decoder. Use of tf.dataset and techniqes for speed improvement such as to-Graph conversion, cashing, prefetching and parallel processing. Replication of the Tensorflow official tutorial with extensive comments.
* **Cifar10:** Image Classification with 10 classes. Use of basic EDA, Data Augmentation and custom CNN for prediction.
## Tabular:
* **House SalePrice Prediction:** Regression problem. EDA and use of a number of Feature Engineering and Feature Selection techniques. Finally use of ANN and XGBoost for prediction
* **Santander Customer Satisfaction:** Classification problem with highly imbalanced data. EDA and use of a number of Feature Engineering and Feature Selection techniques. Two of the most modern gradient boosted decision tree models: XGboost and LightGBM are applied to make predictions with weighting the loss due to the unbalanced data.
* **Categorical Encoding:** Use of a number of categorical encoding techniques including: Ordinal label encoding, Binary encoding, Hash tricks, Encoding based on mean target value, Encoding based on alphabetical order of strings, Encoding of cyclical data
* **Ensemble Titanic:** Use of 2-stages Ensemble Learning on the Titanic Dataset. In the first stage I build a base classification composed of several different classification algorithms with Kflodnd and use a democracy voting for comparison with the final result. Finally, I use an ANN on the result from the first stage along with scalled preprocessed features for the final classification.
