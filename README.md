### Upside-Down Image Detection

My Approach to solving the problem I use transfer learning techniques which provide SOTA (state-of-the-art). There are many pre-trained models like Resnets, VGG, Denseness, etc. The reason why I choose Densenet over Resnet is Dense Networks is a relatively recent implementation of Convolutional Neural Networks, that expand the idea proposed for Residual Networks, which have become a standard implementation for feature extraction on image data. 

Similar to Residual Networks that add a connection from the preceding layer, Dense Nets add connections to all the preceding layers, to produce a Dense Block. The problem that Residual Nets addressed was the vanishing gradient problem that was due to many layers of the network. This helped build bigger and more efficient networks and reduce the error rate on classification tasks on ImageNet. So the idea of Densely Connected Networks, is that every layer is connected to all its previous layers and its succeeding ones, thus forming a Dense Block.


### Dataset
* The dataset that we are using has been derived from the Flicker Faces HQ dataset.
* This Dataset contains 20k images with 10k original and 10k Upside_Down images. Each Image has a size of 256 * 256.

## Train a model to detect if images are upside down using deep learning vision.
* Please choose an image dataset that you are comfortable working with. You have the freedom to select any dataset of your choice.
* One task to perform is to artificially invert a selection of images.
* Create a neural network using Tensorflow, PyTorch, or any other framework of your choice.
* Train it to classify image orientation until a reasonable accuracy is reached
* Look at some of the images that were classified incorrectly
* Answer the following question: what is 1 idea that you have to improve your model's performance on this dataset (you don't have to implement it)
