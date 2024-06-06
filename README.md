# 𝐃𝐈𝐀𝐁𝐄𝐓𝐈𝐂-𝐑𝐄𝐓𝐈𝐎𝐍𝐎𝐏𝐀𝐓𝐇𝐘-𝐃𝐄𝐓𝐄𝐂𝐓𝐈𝐎𝐍 𝐔𝐒𝐈𝐍𝐆 𝐃𝐄𝐄𝐏 𝐋𝐄𝐀𝐑𝐍𝐈𝐍𝐆

![image](https://github.com/Tanwar-12/DIABETIC-RETIONOPATHY-DETECTION/assets/110081008/51eee781-d62f-4c80-8802-84a88b7fab43)

## 𝐈𝐍𝐓𝐑𝐎𝐃𝐔𝐂𝐓𝐈𝐎𝐍:
Diabetic Retinopathy (DR) is a diabetes complication that affects the eyes. It is caused by damage to the blood vessels of the light-sensitive tissue at the back of the eye (retina). DR can lead to blindness if not detected and treated early. Early diagnosis and timely treatment are crucial to prevent vision loss.

## 𝐓𝐚𝐛𝐥𝐞 𝐨𝐟 𝐂𝐨𝐧𝐭𝐞𝐧𝐭𝐬:

1.Business Problem
2.Visualization of Images
3.Image Processing
4.TSNE Visualization
5.Data Augmentation
6.Train Validation Split
7.Resize and save
8.Image Pre Processing and save
9.ResNet50 Models

## 𝐁𝐮𝐬𝐢𝐧𝐞𝐬𝐬 𝐏𝐫𝐨𝐛𝐥𝐞𝐦
This case study is based on a Kaggle Competition conducted 7 months back based on a dataset by Aravind Eye Hospital in India to detect a form of Blindness called Diabetic Retinopathy. https://www.kaggle.com/c/aptos2019-blindness-detection/overview is the link to the Kaggle competition.

## 𝐆𝐎𝐀𝐋 𝐎𝐅 𝐏𝐑𝐎𝐉𝐄𝐂𝐓
The goal here is to Build an Image Classification Model which can take a look at the images and classify the image into one of the 5 classes (0,1,2,3,4). This Image Classification Model can accelerate the process of Blindness Detection in Patients. Currently Doctors review the Image and classify it into one of the classes -

0 - No DR

1 - Mild

2 - Moderate

3 - Severe

4 - Proliferative DR

**Training data contains 3662 images, test data contains 1928 images**

###  𝐕𝐢𝐬𝐮𝐚𝐥𝐢𝐳𝐚𝐭𝐢𝐨𝐧 𝐨𝐟 𝐈𝐦𝐚𝐠𝐞𝐬
![image](https://github.com/Tanwar-12/DIABETIC-RETIONOPATHY-DETECTION/assets/110081008/eb78bd4d-a0f1-4579-808b-64331cfeaa1a)

### 𝐈𝐦𝐚𝐠𝐞 𝐏𝐫𝐨𝐜𝐞𝐬𝐬𝐢𝐧𝐠
* Gaussian Blur

![image](https://github.com/Tanwar-12/DIABETIC-RETIONOPATHY-DETECTION/assets/110081008/0ef6674a-2d19-482c-b79c-11422c7e24a0)

* Gaussian Blur with Circular Cropping
  ![image](https://github.com/Tanwar-12/DIABETIC-RETIONOPATHY-DETECTION/assets/110081008/2e97873f-ba1a-454a-adfa-fb90003fb691)

![image](https://github.com/Tanwar-12/DIABETIC-RETIONOPATHY-DETECTION/assets/110081008/bd275747-8dd1-4683-a38c-990e3562365d)

### 𝐓𝐒𝐍𝐄 𝐕𝐢𝐬𝐮𝐚𝐥𝐢𝐳𝐚𝐭𝐢𝐨𝐧
![image](https://github.com/Tanwar-12/DIABETIC-RETIONOPATHY-DETECTION/assets/110081008/1c3feac5-637c-495a-af29-763f396ec32c)

### 𝐃𝐚𝐭𝐚 𝐀𝐮𝐠𝐦𝐞𝐧𝐭𝐚𝐭𝐢𝐨𝐧
![image](https://github.com/Tanwar-12/DIABETIC-RETIONOPATHY-DETECTION/assets/110081008/900b4380-66b7-433a-989c-f9b4c5d5e89e)

### 𝐓𝐫𝐚𝐢𝐧 𝐕𝐚𝐥𝐢𝐝𝐚𝐭𝐢𝐨𝐧 𝐒𝐩𝐥𝐢𝐭
![image](https://github.com/Tanwar-12/DIABETIC-RETIONOPATHY-DETECTION/assets/110081008/52dc6ed8-2341-49c0-ace3-e7e91820a17e)

![image](https://github.com/Tanwar-12/DIABETIC-RETIONOPATHY-DETECTION/assets/110081008/31b2425d-11c0-458f-bac8-4185065d135f)

### 𝐑𝐞𝐬𝐧𝐞𝐭50 𝐌𝐨𝐝𝐞𝐥 
**ACCURACY**
* Train Cohen Kappa score: 0.980

* Train Accuracy score : 0.965

![image](https://github.com/Tanwar-12/DIABETIC-RETIONOPATHY-DETECTION/assets/110081008/3f631ad1-4b32-4e3d-a8f9-36a03f71f8b0)

**Evaluate Model on Test Data**
![image](https://github.com/Tanwar-12/DIABETIC-RETIONOPATHY-DETECTION/assets/110081008/8227e75f-e7cc-43b3-9137-2ef9ac0d1797)

![image](https://github.com/Tanwar-12/DIABETIC-RETIONOPATHY-DETECTION/assets/110081008/3e2372c7-a8a2-48b8-a526-44cd30c676b6)

* Test Cohen Kappa score: 0.904
  
* Test Accuracy score : 0.839

## 𝐑𝐞𝐬𝐍𝐞𝐭50 𝐌𝐨𝐝𝐞𝐥𝐬 𝐒𝐮𝐦𝐦𝐚𝐫𝐲
+-------+----------------------------+----------------------------+----------------------+-------------------------------+-----------+----------+
| S.No.  |       ResNet50 Model       |      Image Processing     |  Data Augmentation   | Hyperparameters(BS,Opt,lr,ep) | Train QWK | Test QWK |
+-------+----------------------------+----------------------------+----------------------+-------------------------------+-----------+----------+
|   1   | R-P-D-p(0.5)-D-p(0.5)-S(5) |             --             | Hor Flip,Scale 1/255 |      (4,'Adam','1e-4',7)      |   0.912   |  0.905   |
|   2   | R-P-D-p(0.5)-D-p(0.5)-S(5) | Circle Crop, Gaussian Blur | Hor Flip,Scale 1/255 |      (4,'Adam','1e-4',7)      |    0.98   |  0.904   |
+-------+----------------------------+----------------------------+----------------------+-------------------------------+-----------+----------+


### 𝐃𝐄𝐏𝐋𝐎𝐘𝐌𝐄𝐍𝐓
#### Packages and Tools Required:

Python 3.8

Flask

Tensorflow

Keras

OpenCV

#### Built with

Flask

JavaScript

CSS

HTML

## 𝐑𝐄𝐒𝐔𝐋𝐓

![image](https://github.com/Tanwar-12/DIABETIC-RETIONOPATHY-DETECTION/assets/110081008/9f3b3a18-7fd8-4f3e-ae4f-fdf5a362d311)

![image](https://github.com/Tanwar-12/DIABETIC-RETIONOPATHY-DETECTION/assets/110081008/0dd8b3d3-cace-4dc9-bc3b-f52a21a4b2b3)



