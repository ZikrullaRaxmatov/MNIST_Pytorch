# MNIST_Pytorch

Description
This is the MNIST dataset implemented in CNN. The MNIST dataset can predict handwritten (drawn) digits from an image and outputs a prediction from 0-9. The model was built with Pytorch.

To test this model you can open the MNIST_Keras and run it on your device. To test further images just add them to the project and replace my testing with yours.

An example of a handdrawn digit would look like this: Digit 4

Be aware that your images have to have a black background and white line color!

Furthermore your images resolution has to be 28x28px. The line width has to be thick enough to be recognized as a digit.

This CNN model achieves up to 98.9%.

### Accuracy report
SGD(lr=0.01) : 96.17 %
SGD(momentum=0.3) : 96.68 %
Adagrad(lr=0.01) : 98.35 %
RMSProp(lr=0.001) : 98.47 %
Adam(lr=0.001) : 98.58 %

### with dropout
Adam(dropout=0.3) : 98.61 %

### with transfer learning
Adam(lr=0.0001) : 98.94 %
