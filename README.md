# CIFAR10_CNN
This is a model based on convolutional neural network. Here, the concept of pickling is used. Pickling is used to serialize and 
deserialize python objects. We have also used numpy transpose and numpy reshape in the process of data collection.
The image data that we feed into a CNN model is of the form "Channel x Width x Height" or of the form "Width x Height x Channel". 
The labels are numbers where each of these numbers correspond to a single class amongst the list of these classes :
['airplane', 'automobile', 'bird', 'cat', 'deer', 'dog', 'frog', 'horse', 'ship', 'truck'].

Now, We will  the data. The process of reshaping entails two steps : reshaping and transpose.
We reshape the data by dividing it into three vectors(here, each vector corresponds to a channel, the size of the vector is 32 X 32).
Transpose function takes a list of axis.
In the code I have used a funciton display_stats to explore the data, by exploration I mean in a given batch of data what are the image 
labels present. Are these labels random or they follow a specific order, what is the size of the image
I have preprocessed the data that involves data normalization. Normalization technique that is used here is min-max normalization.
We have created a function one hot encoder that returns two dimensional tensor.
CIFAR10 provides 10 different classes of image.


