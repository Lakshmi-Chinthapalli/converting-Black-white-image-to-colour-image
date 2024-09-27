# Colorizing Black & White Images Using Deep Learning
This project demonstrates how to convert black and white (grayscale) images into colorful images using a pre-trained deep learning model. The model used is based on a convolutional neural network (CNN) that has been trained to predict the color distribution of grayscale images, allowing for realistic colorization.
# overview
The colorization of black and white images is a challenging problem due to the inherent ambiguity in predicting the exact color of objects. To tackle this, the project leverages a deep learning-based approach, utilizing a pre-trained Caffe model that has been trained on a large dataset of images to learn the mapping between grayscale inputs and color outputs.

# This approach involves the following steps:

Input the grayscale image: The input image is first converted from grayscale to the LAB color space.
Prediction of color components: The model predicts the 'a' and 'b' components of the LAB color space, which correspond to color information.
Combining with luminance: The original luminance (L channel) is combined with the predicted 'a' and 'b' channels to reconstruct the colorized image.
Output the colorized image: The final image is converted back to the RGB color space for display and saving.

 ![Image Alt](https://github.com/Lakshmi-Chinthapalli/converting-Black-white-image-to-colour-image/blob/eb86ca8d46d1ba695123620f0011db8abcb1ee86/colorized%20image.png)



