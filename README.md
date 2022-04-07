## Upside down image detection using PyTorch

Upside down detector: Train a model to detect if images are upside down
* Pick a dataset of natural images (we suggest looking at datasets on the Hugging Face Hub)
* Synthetically turn some of images upside down. Create a training and test set.
* Build a neural network (using Tensorflow, PyTorch, or any framework you like)
* Train it to classify image orientation until a reasonable accuracy is reached
* Upload the the model to the Hugging Face Hub, and add a link to your model below.


My Approach to solve the problem I use transfer learning techniques which provide SOTA(state-of-the-art).There are many pretrained model like Resnets,VGG,Densenets etc. The reason why i choose Densenet over Resnet is Dense Networks are a relatively recent implementation of Convolutional Neural Networks, that expand the idea proposed for Residual Networks, which have become a standard implementation for feature extraction on image data. Similar to Residual Networks that add a connection from the preceding layer, Dense Nets add connections to all the preceding layers, to produce a Dense Block. The problem that Residual Nets addressed was the vanishing gradient problem that was due to many layers of the network. This helped build bigger and more efficient networks and reduce the error rate on classification tasks on ImageNet. So the idea of Densely Connected Networks, is that every layer is connected to all its previous layers and its succeeding ones, thus forming a Dense Block.

### Dataset
You can Downlaod the Dataset from here.
This Dataset is Derived from Flickers Faces HQ Dataset
This Dataset contains 20k images with 10k original and 10k Upside_Down images.Each Image has size of 256 * 256.
