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








