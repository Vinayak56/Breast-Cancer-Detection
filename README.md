# Breast-Cancer-Detection
Breast cancer is the most frequent cancer among women, with around one in every 19 women at risk. The number of cases of breast cancer is gradually increasing, especially as the population ages. The mammography screening procedure has to be improved and made more efficient. When it comes to medical imaging, there is always space for improvement. Cancer patients' chances of dying are reduced if they are diagnosed early. The goal of this paper is to find the identification of breast cancer using a deep learning model network. Image preparation, categorization, and performance evaluation are all part of the total process. In this research, using the Breast Histopathology Images dataset, we examine the effectiveness of the deep learning model, InceptionResnet, in classifying the presence of IDC(Invasive Ductal Carcinoma). In terms of accuracy, the trained model gave an accuracy of 91%.

## Dataset
Breast Histopathology Images, a datset available on Kaggle has been used for this project. in this, each patch’s file name is of the format: uxXyYclassC.png — > example 10253idx5x1351y1101class0.png, wherehere u is the patient ID (10253idx5), X is the x-coordinate of where this patch was cropped from, Y is the y-coordinate of where this patch was cropped from, and C indicates the class where 0 is non-IDC and 1 is IDC.

**Link:** https://www.kaggle.com/paultimothymooney/breast-histopathology-images

## Model
InceptionResnet has been used for training the model.

## Working Demonstration
