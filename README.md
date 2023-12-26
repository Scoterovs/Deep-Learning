# Deep-Learning
Apply artistic style transfer to an image using deep neural networks.
# Example code using Neural Style Transfer (NST)
# (Make sure to use a pre-trained model or implement one)
from keras.preprocessing import image
from keras.applications.vgg19 import VGG19, preprocess_input
from keras.models import Model
import numpy as np

base_image_path = 'base_image.jpg'
style_reference_image_path = 'style_reference_image.jpg'

# Implement NST logic (e.g., load model, preprocess images, perform style transfer)
