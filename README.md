# Image-Classification-of-Eye-Disease

[![Open In Colab](https://colab.research.google.com/assets/colab-badge.svg)](https://colab.research.google.com/github/Tamago55/AI-Image-Classfication-of-Eye-Disease/blob/master/Image_Detection_for_Eye_Disease.ipynb)

## 1. Introduction
This program is designed to classify images of eye diseases into five categories based on severity levels ranging from 0 to 4. By preparing a dataset divided into these categories, the program learns to classify similar images of eye diseases into these five stages. Moreover, it enables the analysis of each severity level's images through comparison, understanding misclassifications with a confusion matrix, and identifying focal points in images using attention maps. (Actual eye images are not uploaded due to privacy concerns.)

<img src="https://raw.githubusercontent.com/Tamago55/AI-Image-Classfication-of-Eye-Disease/main/images/matrix.png" width="80%" alt="matrix">

## 2. How to Use
Prepare the train and test sets of eye images categorized into five severity levels and input their directories into the `Image_Detection_for_Eye_Disease.ipynb` file to execute the program. By default, the directory is set to `/content/drive/My Drive/AAAI/DR_data_cropped_classes`, under which there should be `train` and `test` folders containing subfolders named 0, 1, 2, 3, and 4. Reference empty files are provided in the same directory for guidance. Given that data augmentation is applied, it is possible to start training with approximately 100 images per class.
