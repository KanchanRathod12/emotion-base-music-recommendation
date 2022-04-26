# emotion-base-music-recommendation
The aim of this project is to develop a system that will recommend music based on facial expressions. Layers of convolution neural network are used for the expression detection and are optimized with Adam to reduce overall loss and improve accuracy. YouTube song playlist recommendation is an application of a face recognition system based on a neural network. We use streamlit-webrtc to design the web frame for the song recommendation system. For face detection, we used the Kaggle-FER2013 dataset, and images in the dataset are classified into seven natural emotions of a person. The system captures the emotional state of a person in real-time and generates a playlist of youtube songs based on that emotion.


Import libraries
Streamlit, NumPy, Matplot, Keras ,Pandas,Tensorflow


 Overview of emotion base music recommendation
 
![emotion based music recommendation1 (111)](https://user-images.githubusercontent.com/104412295/165359359-e1d854fb-fd98-4fef-b1c4-61702817fffe.jpg)


Sample images in FER dataset

![output1](https://user-images.githubusercontent.com/104412295/165358450-9907d5d4-9924-4bae-9a66-3eff532b021f.png)

System architecture of a model



![Fig main project11](https://user-images.githubusercontent.com/104412295/165360062-e62b7029-de7e-40f1-9cd7-e7b034637c7a.jpg)


output images of mediapipe holistic

![medipipe output1](https://user-images.githubusercontent.com/104412295/165358823-fa578765-0e94-4dcd-858e-c095ebe376b7.png)


Face Mesh through mediapipe and key value for each connecting point of a face


![Screenshot (241)](https://user-images.githubusercontent.com/104412295/165360479-dec0d0ba-63f1-4538-8dcc-7243c4519e15.png)



The output plot of accuracy and loss

![output accuracy and loss](https://user-images.githubusercontent.com/104412295/165358256-ce18da47-a600-4577-91b5-32fefe8f7ef8.png)




Confusion matrix for seven emotions

![confusion matrix11](https://user-images.githubusercontent.com/104412295/165359173-76e27f02-92a5-48b1-8941-974b7275f813.png)








