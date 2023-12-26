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
In this task, I have designed a transfer learning-based approach using VGG-16 for Task 1. The final architecture is as below:
![Task-2-Archi](https://github.com/Deep-Hassan/Basic-CV/assets/154924122/c083d52f-83c9-4c79-b580-0218a5adf777)

The training and Validation curve for the same is as below:
![Task-2-Trainning](https://github.com/Deep-Hassan/Basic-CV/assets/154924122/f0d7b7e7-b67c-4197-8650-3f15a02f0920)

The confusion matrix:
![CM-task2](https://github.com/Deep-Hassan/Basic-CV/assets/154924122/4a99a10a-629e-4be0-b3d3-45ece2503af8)

## Task-3
In this task, an Image Retrieval System has been designed where the query image is provided as an input and the images based on similarity are shown just like in Google Lens.
The system has been designed with a custom image data loader, followed by a Resnet-50-based backbone for feature extraction followed by the similarity determination based on Euclidean distance between the feature volumes. The results for the butterfly query image are as below, for further details kindly refer the attached notebook.
![Task-3](https://github.com/Deep-Hassan/Basic-CV/assets/154924122/eb5f00e5-7fd3-4ac7-b119-f616ffee4d48)

















