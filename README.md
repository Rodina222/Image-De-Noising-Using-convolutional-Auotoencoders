# Image-De-Noising-Using-convolutional-Auotoencoders
This Python code demonstrates how to build an autoencoder using Keras and TensorFlow to encode and decode Fashion MNIST images. It starts by loading the Fashion MNIST dataset, which consists of 60,000 training images and 10,000 test images of 10 different categories of clothing. It then plots the first 25 training images to ensure they are grayscale images.

The code then normalizes and flattens all images in the dataset and builds an autoencoder model with 3 hidden layers. The model takes the flattened input image and encodes it into a lower-dimensional representation before decoding it back to the original image using a reconstruction layer. It uses the mean squared error loss function and the Adam optimizer for training.

Finally, the code reconstructs a few test images using the trained autoencoder model and plots the original, encoded, and reconstructed images side-by-side to visualize the performance of the autoencoder. The encoded images are visualized as a 4x8 grid of grayscale pixels, representing the lower-dimensional representation of the original image.
