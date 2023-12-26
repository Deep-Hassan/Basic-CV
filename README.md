# Basic-CV-Tasks for Exploring Deep Learning For Computer Vision
There are 03 different Tasks designed for practice and understanding the basics of deep learning for Computer Vision.
## Task-1
I have designed a simple convolution neural network for numeric digit classification. The provided dataset consists of three classes and the structure is as below:

hand_written_digits/
    0_digits/
        File1.jpg
        File2.jpg
    1_digits/
        File1.jpg
        File2.jpg
    2_digits/
        File1.jpg
        File2.jpg
#### Step-1:
For the division of the dataset in training, Test, and Validation Split while keeping the basic structure of the folder and subfolders the same I have used python_splitter.
For the installation of the same, I have used! pip install python_splitter.
It will result in the creation of a folder in the main directory having the train, test, and valid folders.

#### Step-2:
Next, I used the TensorFlow/Keras data generator functionality and created the dataloader for train, validation, and testing.

#### Step-3:
I have designed a basic CNN architecture from which the basic diagram is as below:

![Task-1-Archi](https://github.com/Deep-Hassan/Basic-CV/assets/154924122/23af4612-07e2-4855-95fe-a19104b57339)

#### Step-4:
The algorithm has been trained and the training and validation curve and Confusion Matrix are as below:
![Task-1-Trainning](https://github.com/Deep-Hassan/Basic-CV/assets/154924122/a81751ce-d6e4-431a-9007-fe4d8e69d7bf)
![CM-task1](https://github.com/Deep-Hassan/Basic-CV/assets/154924122/5b6e4258-7e0c-4268-9ee5-13d5928e6a2c)

## Task-2
In this task, I have designed a transfer learning-based approach using VGG-26 for Task 1. The final architecture is as below:










