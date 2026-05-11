# Gesture-Recognition-CNN-
Gesture Recognition using Hand  Movements via Convolutional Neural  Networks (CNN)  + MATLAB use AI 

Abstract 

Gesture recognition using hand movements has become increasingly important in various 
applications, including human-computer interaction, virtual reality, and robotics. Convolutional 
Neural Networks (CNN) have been widely used for image recognition and have recently shown 
great potential for gesture recognition tasks.  
This project aims to develop a CNN-based system for recognizing hand gestures using images 
captured from various angles and under different lighting conditions. To achieve this, a large 
dataset of hand gesture images, such as the ASL Fingerspelling Spelling database, was used to 
train and evaluate the proposed system.  
The proposed system has many potential applications, such as controlling smart home devices, 
virtual reality interactions, and gaming experiences without the need for external controllers. This 
project demonstrates the effectiveness of using CNNs for gesture recognition and highlights the 
potential of this technology for developing intelligent systems that can better understand and 
interpret human gestures. 
Keywords: Gesture recognition, hand movements, Convolutional Neural Networks, image 
recognition, ASL Fingerspelling Spelling,

Introduction 

In recent years, gesture recognition using artificial intelligence has gained significant attention in 
various fields, such as human-computer interaction, virtual reality, and robotics. The ability to 
recognize and interpret human gestures through hand movements has the potential to revolutionize 
the way we interact with technology, making it more intuitive and natural. 
Convolutional Neural Networks (CNNs) have shown great potential in recognizing hand gestures 
from images, and this project aims to develop a CNN-based system to recognize hand gestures 
using images captured from various angles and under different lighting conditions. 
The importance of hand gesture recognition in various fields, such as human-computer interaction, 
virtual reality, and robotics, cannot be overstated. The ability to recognize and interpret hand 
gestures has the potential to change the way we interact with technology, making it more intuitive 
and natural. With the advances in artificial intelligence and machine learning, CNNs have emerged 
as a powerful technique for recognizing hand gestures from images. [1] 
The main challenge in hand gesture recognition is the complexity of hand movements and 
variations in lighting, background, and clothing, which can affect recognition accuracy. Therefore, 
this project focuses on developing a CNN-based system to recognize hand gestures using images 
captured from various angles and under different lighting conditions. The goal of this project is to 
improve recognition accuracy and performance by focusing on deep learning techniques and 
improving the accuracy of the model. [2] 
The technique used in this project involves several basic steps to improve the accuracy of hand 
gesture recognition using CNNs. The model used in this project consistsof several convolutional 
and pooling layers, followed by fully connected layers for hand gesture classification. These layers 
process the images and extract the necessary information for hand gesture recognition. 
Improving the accuracy of hand gesture recognition is a significant challenge, particularly for Practical applications of hand gesture recognition using CNNs include medical, industrial, and 
security applications. These applications can benefit significantly from hand gesture recognition 
technology, which can be used for disease diagnosis, robot control, and security enhancement. 
hand gesture recognition using artificial intelligence has significant potential in various fields, 
including human-computer interaction, virtual reality, and robotics. CNNs are a powerful 
technique for recognizing hand gestures from images, and this project aims to develop a CNN
based system to recognize hand gestures using images captured from various angles and under 
different lighting conditions. Improving hand gesture recognition accuracy remains a significant 
challenge, but the development of advanced techniques and the continuous improvement of the 
model can lead to significant improvements in this area 

Aims and objectives :
This project aims to introduce the application of gesture recognition using hand movements via 
convolutional neural networks (CNN) in MATLAB with the ASL Finger Spelling database. It 
discusses the potential applications of this technology in fields such as robotics, e-learning, smart 
homes, and sign language education. The text emphasizes the importance of expertise in 
information technology and artificial intelligence for the development of this technology and the 
significant effort required in collecting and preparing appropriate data, tuning neural network 
parameters, and improving performance. 
The objectives of the project are to provide an understanding of the following: 
• The concept of gesture recognition using hand movements via convolutional neural 
networks (CNN) in MATLAB using the ASL Finger Spelling database 
• The potential applications of this technology in various fields 
• The importance of expertise in information technology and artificial intelligence for 
developing this technology 
• The significant effort required in collecting and preparing appropriate data for system 
training, tuning neural network parameters, and improving their performance. 

Literature Review 
The following studies have been conducted on the ASL-RGB-Depth-Fingerspelling-Spelling 
dataset to improve the accuracy of American Sign Language (ASL) fingerspelling recognition 
using deep learning techniques: 
1. "Real-Time American Sign Language Fingerspelling Recognition using Deep Convolutional 
Neural Networks" uses deep neural networks to improve the real-time recognition of American 
Sign Language fingerspelling. The system was evaluated using the ASL Fingerspelling Spelling 
dataset and achieved a high classification accuracy of 98.9% [5] 
2. "A Survey of Deep Learning Techniques for American Sign Language Recognition" reviews 
the different techniques for recognizing American Sign Language using deep learning techniques. 
The proposed methods and techniques were evaluated in several previous studies, and the 
evaluation results showed that deep learning techniques led to significant improvements in the 
accuracy of ASL recognition, especially using various deep neural networks [6] 
3. "FingerSpelling Recognition using a Hybrid CNN-LSTM Model with AttentionMechanism" 
uses a hybrid model consisting of convolutional neural networks, long short-term memory 
networks, and attention mechanism to improve the accuracy of recognizing American Sign 
Language fingerspelling. The system was evaluated using the ASL Fingerspelling Spelling dataset 
and achieved a high classification accuracy of 99.4% [7] 
4. "Real-Time American Sign Language Fingerspelling Recognition using a Lightweight CNN" 
uses a lightweight deep neural network to improve the real-time recognition of American Sign 
Language fingerspelling. The system was evaluated using the ASL Fingerspelling Spelling dataset 
and achieved a high classification accuracy of 98.8%  [7] 
5. "Robust Deep Learning Framework for American Sign Language Recognition using 
Fingerspelling" uses a robust deep learning framework to improve the accuracy of recognizing 
American Sign Language fingerspelling. The system was evaluated using the ASL Fingerspelling 
Spelling dataset and achieved a high classification accuracy of 99.2% [8] 
6. "Real-Time Recognition of American Sign Language Fingerspelling using Deep Learning on 
Low-Power Devices" uses deep learning techniques on low-power devices to improve the real
| P a g e
4
time recognition of American Sign Language fingerspelling. The system was evaluated using the 
ASL Fingerspelling Spelling dataset and achieved a high classification accuracy of 98.7%. This 
technique can be used in mobile phones and wearable devices, which are considered low-power 
[9] 
Here is the table (1) comparing the studies on American Sign Language recognition using deep 
neural networks: 
Table 1: comparing the studies 
Study 
Number Date 
Technique used 
Accuracy 
1 
2018 
Deep CNNs 
98.9% 
Notes 
None 
2 
2019 
Various - 
Accuracy not evaluated in this 
study 
3 
2019 
Hybrid CNN-LSTM 
99.4% 
None 
4 
2018 
Lightweight CNN 
98.8% 
May need to improve accuracy in 
different lighting conditions 
5 
2020 Robust Deep Learning 
Framework 
99.2% 
None 
6 
2019 Deep Learning on Low
Power Devices 
98.7% 
May need to improve accuracy in 
different lighting conditions 
Note: It should be noted that some studies used different techniques, and accuracy was not 
evaluated in some studies. Also, the accuracy mentioned in the studies may have been evaluated 
using a specific dataset and may not apply to other datasets. 
The studies conducted on the ASL-RGB-Depth-Fingerspelling-Spelling dataset demonstrate the 
effectiveness of deep learning techniques in improving the accuracy of American Sign Language 
fingerspelling recognition. The use of various deep neural networks, such as convolutional neural 
networks and long short-term memory networks, has led to significant improvements in the real
time recognition of ASL fingerspelling. The results of these studies show that deep learning 
techniques can be used to create robust and accurate ASL recognition systems for various 
applications, including mobile phones and wearable devices. However, further research is needed 
| P a g e
5
to improve the accuracy of recognizing other ASL gestures and to develop more efficient and 
lightweight models for low-power devices.

Observation :
Hand gestures are a common way of conveying information or commands in various applications 
such as sign language or gaming. Common hand gestures include finger spelling, pointing, waving, 
or making shapes with hands. Accurate and efficient recognition of hand gestures is crucial for 
improving human-computer interaction. With the advances in artificial intelligence and machine 
learning, techniques such as convolutional neural networks (CNNs) have emerged as powerful 
tools for recognizing hand gestures from images captured from various angles and under different 
lighting conditions. The ability to recognize and interpret hand gestures has the potential to change 
the way we interact with technology, making it more intuitive and natural.

Techniques 
1. The ASL Finger Spelling Database: This specialized database contains images of finger 
and hand movements used to form letters, numbers, and words in American Sign 
Language (ASL). It serves as the source of appropriate data for training and testing the 
system. 
2. MATLAB: This programming language and development environment is used to 
implement the Convolutional Neural Network (CNN) model, preprocess data, and evaluate 
system performance. MATLAB offers various functions and tools for image processing, 
machine learning, and deep learning applications. 
3. Convolutional Neural Networks (CNN): CNN is a type of neural network utilized 
for image recognition and classification, and it is the primary algorithm employed in this 
project for recognizing hand gestures and converting them into written text. 

4. Deep Learning Toolbox: This MATLAB toolbox is used for designing, training, and 
evaluating deep neural networks, including CNNs.

Methodology 
The methodology for this project can be broken down into three main parts : 
Dataset 
The proposed system was trained and evaluated using the ASL-RGB-Depth-Fingerspelling
Spelling database. This dataset comprises a vast collection of hand gesture images captured from 
various angles and under varying lighting conditions, as shown in Figure (1). To ensure 
consistency, the dataset was preprocessed by standardizing the image format and size. 
Additionally, the images underwent normalization to account for differences in lighting and contrast. The final dataset was divided into training and testing sets, with 80% of the data used for 
training and 20% for validation.
<img width="795" height="210" alt="image" src="https://github.com/user-attachments/assets/0116600b-ecf3-4c96-a047-d570829b62a5" />
The ASL-RGB-Depth-Fingerspelling-Spelling database is a popular dataset for training and 
evaluating American Sign Language recognition systems. It is widely used in research due to its 
comprehensive collection of hand gesture images that are captured from different views and under 
various lighting conditions. This diversity in the dataset allows for the creation of robust models 
that can generalize well to different scenarios. 
The dataset was divided into training and testing sets. The training set, which comprises 80% of 
the data, was used to train the model, while the remaining 20% was used for validation. Splitting 
the dataset into training and validation sets is crucial in evaluating the model's performance and 
preventing overfitting. Overfitting occurs when the model becomes too specialized in the training 
data and fails to generalize well to new data. 
The ASL-RGB-Depth-Fingerspelling-Spelling database is a valuable resource for training and 
evaluating American Sign Language recognition systems. Preprocessing the dataset is essential to 
ensure that the images are consistent and normalized, allowing the model to learn efficiently. 
Splitting the dataset into training and testing sets is crucial in evaluating the model's performance 
and preventing overfitting. The accuracy metric is often used to evaluate the model's performance, 
providing a measure of how well the model can generalize to new data.

Model 
The table (2) represents a Convolutional Neural Network (CNN) model designed in MATLAB. 
The model is designed to process images of size 224x224x3 and consists of several layers that 
perform various operations on the input data to extract features and classify them into different 
categories. The following is a detailed description of each layer in the model: 
1. ImageInputLayer: This layer defines the input size of the images. In this case, the input 
images have a size of 224x224x3, where 224x224 represents the image resolution and 3 
represents the number of channels (RGB). 
2. Convolution2dLayer: This layer performs convolution operations on the input data to 
extract features. The layer has 3 arguments: filter size, number of filters, and padding. In 
this model, the first convolutional layer has a filter size of 3x3, 64 filters, and padding set 
to 'same'. The padding ensures that the output feature maps have the same size as the input 
feature maps. 
3. ReLU Layer: This layer applies the Rectified Linear Unit (ReLU) activation function to 
the output of the preceding convolutional layer. The ReLU function introduces non
linearity into the model and is used to increase the model's capacity to learn complex 
features.
4. MaxPooling2dLayer: This layer performs max pooling on the output of the preceding 
ReLU layer. The layer has two arguments: pooling size and stride. In this model, the max 
pooling layer has a pooling size of 2x2 and a stride of 2. The max pooling operation reduces 
the spatial dimensions of the feature maps while retaining the most important features. 
5. The model has multiple convolutional, ReLU, and max pooling layers, each with different 
filter sizes, number of filters, and padding. These layers are designed to extract increasingly 
complex and abstract features from the input images. 
6. FullyConnectedLayer: This layer connects all the neurons from the previous layer to the 
current layer, performing a matrix multiplication on the input data. In this model, the fully 
connected layer has 4096 neurons. 
7. DropoutLayer: This layer randomly drops out a specified percentage of the neurons in the 
preceding layer during training. This technique is used to prevent overfitting by reducing 
the model's sensitivity to the specific weights of individual neurons. 
8. SoftmaxLayer: This layer applies the softmax function to the output of the preceding layer, 
producing a probability distribution over the classes. 
9. ClassificationLayer: This layer performs the final classification of the input data into 
different classes based on the probability distribution produced by the softmax layer.

The model is a Convolutional Neural Network (CNN) designed for image classification of size 224×224×3. It uses multiple convolutional and max pooling layers to extract important image features, followed by fully connected layers for classification.

ReLU activation is used to introduce non-linearity, while max pooling reduces spatial dimensions and improves efficiency. Dropout layers are applied to reduce overfitting and improve generalization.

The final layer uses Softmax activation to produce probability distributions over classes, and the output classification is based on the highest probability. The number of output classes is defined in the last dense
.

Filter sizes (3×3 to 7×7), increasing number of filters, and “same” padding help preserve spatial structure while extracting deep features. Overall, this architecture is a standard and effective CNN design for image classification tasks.
contrast. The final dataset was divided into training and testing sets, with 80% of the data used for 
training and 20% for validation.
