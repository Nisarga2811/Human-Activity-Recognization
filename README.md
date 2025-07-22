# Human-Activity-Recognization
It is the software built using machine learning algorithm called LSTM and built app using Java
It is zip format.

Problem Statement 
The aim of the project is to design and implement a real time Human Activity 
Recognition system that leverages sensor data to accurately classify physical activities, addressing challenges such as data variability, ensuring real-time processing capabilities, and achieving consistent performance across diverse users and environments. 

Sensors like Accelerometer, Gyroscope, Magnetometer etc is used which are embedded in the smartphone.

We can predict the activity by holding the phone in right or left pocket.

Human Activity Recognization app--> Contain the code for creating the Application for recognizing the Activity performed by the human using Java.

Human-Activity-Recognition-on-Android-master --> Contain the Machine learning code in python for training.

Architecture: 
Layer 1: The first layer is a LSTM layer for learning from sequence of 100 points at each timestamp are returns the sequence mapping as well. 
Layer 2: Flatten layer is used to 2 dimensional (Number of timestamps, Number of features) output from above LSTM layer and convert it into 1-d vector 
Layer 3: From this layer onwards the classifier part is starting which is a Dense layer that takes flatten output from above layer and pass it to Layer 4. 
Layer 4: This is softmax layer taking input from Layer 3 and predict the probability corresponding to each activities.

The dataset has been recored on following activities:
Walking
Standing
Jogging
Sitting
