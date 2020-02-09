# Building_Neural_Network_For_Image_Classification.
A detailed overview of under the hood working of a L layer neural network.

## Introduction

Recent advances in deep learning made tasks such as Image and speech recognition possible.

***Deep Learning: A subset of Machine Learning Algorithms that is very good at recognizing patterns but typically requires a large number of data.***

Deep learning excels in recognizing objects in images as it’s implemented using 3 or more layers of artificial neural networks where each layer is responsible for extracting one or more feature of the image.

***Neural Network: A computational model that works in a similar way to the neurons in the human brain. Each neuron takes an input, performs some operations then passes the output to the following neuron.***

![nn](https://user-images.githubusercontent.com/44902363/74097097-18826900-4b2e-11ea-8275-d3b186965bfc.png)


To do so, we first need to teach the computer how a cat, a dog, a bird, etc. look like before it being able to recognize a new object. The more cats the computer sees, the better it gets in recognizing cats. This is known as supervised learning. We can carry this task by labeling the images, the computer will start recognizing patterns present in cat pictures that are absent from other ones and will start building its own cognition.


## Machine Learning For Image Recognition

Computers are able to perform computations on numbers and is unable to interpret images in the way that we do. We have to somehow convert the images to numbers for the computer to understand.

There are two common ways to do this in Image Processing:

- **Using Greyscale:**

The image will be converted to greyscale (range of gray shades from white to black) the computer will assign each pixel a value based on how dark it is. All the numbers are put into an array and the computer does computations on that array. This is how the number 8 is seen on using Greyscale:

![gray](https://user-images.githubusercontent.com/44902363/74097127-a3fbfa00-4b2e-11ea-89cb-8a366936e1b2.png)


- **Using RGB Values:**

Colors could be represented as RGB values (a combination of red, green and blue ranging from 0 to 255). Computers could then extract the RGB value of each pixel and put the result in an array for interpretation.
When the computer interprets a new image, it will convert the image to an array by using the same technique, which then compares the patterns of numbers against the already-known objects. The computer then allots confidence scores for each class. The class with the highest confidence score is usually the predicted one.

***Note- the dataset which is provided to us contain image in RGB value***

![rgb](https://user-images.githubusercontent.com/44902363/74097176-1076f900-4b2f-11ea-8b21-e026e53279ea.jpg)


## Making L Layer Neural Network

![neural_net](https://user-images.githubusercontent.com/44902363/74097295-76b04b80-4b30-11ea-8d01-97b343b15484.gif)

Various helper function is requried to implement the L layer neural network.

A detail about each helper function is given in the **Building_Neural_Network_Step_By_Step.ipynb**

Hence there we see how each function is contributing in making up the neural network.

After that we implemented those function in the **Building_Neural_Network_For_Image_Classsification**

Thus we saw how we used neural network for image classification.Later we will work on Convolution Neural Network which is usedn for image recognition.

### ShubhangiDabral13
