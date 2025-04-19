This repository presents a deep learning project based on a Convolutional Neural Network (CNN) for detecting forest fires from images. Developed using TensorFlow and Keras, the model is trained on The Wildfire Dataset.

Project Structure:

Week 1 Highlights:

Retrieved and extracted The Wildfire Dataset via KaggleHub.

Displayed sample images to understand the dataset visually.

Verified GPU support for enhanced training performance.

Identified the two classes in the dataset: fire and nofire.

Showcased class-wise sample images using Matplotlib.

Week 2 Enhancements:

Integrated image preprocessing using ImageDataGenerator.

Applied normalization by rescaling pixel values.

Configured data to load in batches of 32 for optimized training.

Enabled data shuffling to minimize overfitting risks.

Constructed a deeper CNN architecture with three Conv2D and MaxPooling2D layers.

Introduced a Dropout layer to further combat overfitting.

Set classification mode to binary for distinguishing between fire and nofire.

Week 3 Enhancements:

Configured the CNN with the Adam optimizer and binary cross-entropy loss function.

Trained the model for 12 complete cycles (epochs) while validating it side by side.

Plotted the accuracy and loss graphs to evaluate training and validation trends.

Used the test data to assess the model's final accuracy.

Saved the trained model file for reuse or deployment.

Developed a custom function that accepts a new image and predicts whether it shows fire or not.
