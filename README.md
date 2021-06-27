# Street-Number-classification-with-CNN
Capstone project of Coursera Getting Started with Tensorflow 2
Objective: GOal was to classfy street sign images captured from satellite.
Size of the data: Train data has 73257 images and test data has 
Preprocessing of the data: The dataset is in .mat format. I converted the rgb image to grayscale image. Then normalized the image.
Using Neural Network for classification: For Neural Network I used 2 hidden layers, 1 input and output layer. 32 by 32 image are converted to 512 and 256 dimensional layers and finally 11 dimensional output layer (For digit 0 to 10).

For CNN I used Conv2D, Dropout, Batch Normalization layer etc. I was able to achieve 89% accuracy with only 10 epochs, a much higher accuracy than ann (74%). Only drawback is CNN took a higher training time.
