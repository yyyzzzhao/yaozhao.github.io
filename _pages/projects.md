---
layout: archive
title: "Projects"
permalink: /projects/
author_profile: true
---



* Staging liver fibrosis, Oct 2017 - May 2018
  * Based on ultrasound images, we applied machine learning to stage liver fibrosis. We extract texture, intensity and wavelet features according to characteristics of liver ultrasound image. Then a sparse representation algorithm was applied to select mast relative features and finally a SVM classifier was used to stage liver fibrosis.
  * As contrast, we transfer a pretrained VGG19 network and replaced the last fully connected layer. Our model is based on tensorflow.
 
* Sparse representation algorithm for HCC precision diagnosis
  * Extract texture features from ultrasound images tumor area by dictionary learning. Regress classification labels using features and sort regression coefficients as feature selection result. Classify images by using SVM.
  * Combine multi modality images features collaborating parameterize the model.
  
* Prediction of lymph node metastasis in breast tumor
  * Enable the Resnet compatible multi-modal inputs and train model with transfer learning stratage.
  * Visualize the intermedia convolution layer by Grad-Cam and further apply region average pooling.
  
* Ultrasound image reconstruction
  * Generate new modality US image using GAN model.
  * This project is in progress.