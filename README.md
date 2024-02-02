# Binary classification based on gender

This Jupiter notebook contains an overview of how to implement the VGG16 model to identify the gender of the person in the picture. It offers a step-by-step tutorial and detailed explanations of the code and the concepts used.

Vgg16 is a convolutional neural network is also known as a ConvNet, which is a kind of artificial neural network. A convolutional neural network has an input layer, an output layer, and various hidden layers. VGG16 is a type of CNN (Convolutional Neural Network) that is considered to be one of the best computer vision models to date. The creators of this model evaluated the networks and increased the depth using an architecture with very small (3 × 3) convolution filters, which showed a significant improvement on the prior-art configurations. They pushed the depth to 16–19 weight layers making it approx — 138 trainable parameters.

## In here you will find
- **Face detection setup**: how to use OpenCV to detect the faces in the pictures, preparing them for binary classification.
- **Data augmentation**: how to increase the size and variability of the training set using differeny techniques.
- **Use of the VGG16 model**: how to set up the VGG16 model and preparing it for binary classification.
- **Plots of the results**: for a better understanding of the predictions, there are several plots that visualize the predictions VS the actual values from the validation set.

## Libraries and dependencies
- TensorFlow 
- NumPy 
- Pandas 
- Matplotlib and Seaborn 
- OpenCV  
- Augmentor
- [robots.ox.ac.ik]("http://www.robots.ox.ac.uk/~vgg/data/vgg_face/vgg_face_dataset.tar.gz") database 
