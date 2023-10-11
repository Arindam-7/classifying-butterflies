# Butterfly Categorization using MobileNet

This project demonstrates my work on butterfly categorization using the MobileNet model. The goal was to classify different species of butterflies based on the provided images.

### About the Project

I utilized the MobileNet model, a popular deep learning architecture, to classify butterfly images into distinct categories. The MobileNet model was pre-trained and loaded using TensorFlow.

### Usage

1. **Dependencies**: Ensure you have the necessary dependencies installed. The code in the Jupyter notebook `Butterfly Categorization.ipynb` takes care of this. You can access the notebook [here](https://colab.research.google.com/drive/1ISpPnj4BBvvoZwddzEFwaQoASu_40vWD).

2. **Model**: The MobileNet model was chosen for its efficiency and accuracy in image classification tasks.

3. **Data**: The [train and test data](https://drive.google.com/drive/folders/1HuA3vjxzOfNKhiYxFt0HfUZQkaoeY0yk?usp=sharing) is included on google drive. 

4. **Preprocessing**: Images were resized to a consistent size of 300x300 pixels to maintain aspect ratio and then converted to the RGB color space.

5. **Classification**: The MobileNet model was used to predict the butterfly species for both the test set and a custom set of images.

6. **Evaluation**: Classification reports were generated to evaluate the model's performance on both the training and testing sets.

7. **Output**: The predicted labels for a set of images were saved to a CSV file named `MobileNet.csv`.

### Dataset

[Download the Dataset from here](https://drive.google.com/drive/folders/1HuA3vjxzOfNKhiYxFt0HfUZQkaoeY0yk?usp=sharing)


## MobileNet

The `tf.keras.applications.MobileNet` function is used to instantiate the MobileNet architecture. Key parameters and features include:

- **Alpha**: Controls the width of the network by adjusting the number of filters in each layer.
- **Depth Multiplier**: Adjusts the depth of the network using depthwise convolution.
- **Dropout Rate**: Utilizes dropout for regularization.
- **Pre-trained Weights**: Supports pre-training on ImageNet.
- **Pooling Options**: Allows different pooling modes for feature extraction.

