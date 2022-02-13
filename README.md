# Breast-Cancer-Detection
Breast cancer is the most frequent cancer among women, with around one in every 19 women at risk. The number of cases of breast cancer is gradually increasing, especially as the population ages. The mammography screening procedure has to be improved and made more efficient. When it comes to medical imaging, there is always space for improvement. Cancer patients' chances of dying are reduced if they are diagnosed early. The goal of this paper is to find the identification of breast cancer using a deep learning model network. Image preparation, categorization, and performance evaluation are all part of the total process. In this research, using the Breast Histopathology Images dataset, we examine the effectiveness of the deep learning model, InceptionResnet, in classifying the presence of IDC(Invasive Ductal Carcinoma). In terms of accuracy, the trained model gave an accuracy of 91%.

## Dataset
Breast Histopathology Images, a datset available on Kaggle has been used for this project. in this, each patch’s file name is of the format: uxXyYclassC.png — > example 10253idx5x1351y1101class0.png, wherehere u is the patient ID (10253idx5), X is the x-coordinate of where this patch was cropped from, Y is the y-coordinate of where this patch was cropped from, and C indicates the class where 0 is non-IDC and 1 is IDC.
![153760048-9915e5a7-544d-4e47-a230-bf7b3aef13a4](https://user-images.githubusercontent.com/71933031/153769809-1c59f2f8-c7e9-4f62-8a1e-3878acde2124.jpg)


**Link:** https://www.kaggle.com/paultimothymooney/breast-histopathology-images

## Model
InceptionResnet has been used for training the model.

![153760062-7b107601-468c-4473-8754-fc01ba9c093d](https://user-images.githubusercontent.com/71933031/153769808-d19a1d96-5743-4447-a2dc-2e095b68367a.jpg)

## Working Demonstration
https://user-images.githubusercontent.com/71933031/153769812-0d10d712-c9f9-4998-a296-007d0948a5e7.mp4
