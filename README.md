# Deep Learning Batik Classification

This repository contains a Deep Learning model for classifying Batik Nusantara (Indonesian Batik) images into 20 different classes. The classes and their names are as follows:

'1. Aceh PintuAceh'
2. 'Bali Barong'
3. 'Bali Merak'
4. 'DKI OndelOndel'
5. 'JawaBarat Megamendung'
6. 'JawaTimur Pring'
7. 'Kalimantan Dayak'
8. 'Lampung Gajah'
9. 'Madura Mataketeran'
10. 'Maluku Pala'
11. 'NTB Lumbung'
12. 'Papua Asmat'
13. 'Papua Cendrawasih'
14. 'Papua Tifa'
15. 'Solo Parang'
16. 'SulawesiSelatan Lontara'
17. 'SumateraBarat Rumah Minang'
18. 'SumateraUtara Boraspati'
19. 'Yogyakarta Kawung'
20. 'Yogyakarta Parang'

## Dataset
The raw dataset used for training and testing the model is available on Kaggle. The following is the [link](https://www.kaggle.com/datasets/hendryhb/batik-nusantara-batik-indonesia-dataset). The dataset is divided into training and testing sets, in .jpg format and 224 x 224 pixels.


## Model Architecture
The model architecture used for this classification task is a type of feedforward neural network known as a multi-layer perceptron (MLP). It employs a Sequential model consisting of dense layers for feature extraction and classification. The model is compiled with the Adam optimizer and categorical cross-entropy loss function for training.

## Performance
While the current accuracy results may not meet expectations, there is still room for improvement. The model's performance can be enhanced through further optimization techniques and adjustments in the training process. Contributions and suggestions for improvement are welcome.

Please feel free to explore the repository and contribute to the development of this Deep Learning model for Batik classification.
