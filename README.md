Project Overview
This project involves training and evaluating three deep learning models (ResNet, Xception, and DenseNet) for multi-class image classification. The models are built and fine-tuned using the Keras and TensorFlow frameworks. The dataset, FaceScrub, contains images categorized by different classes. The goal is to achieve high accuracy in classifying images while comparing the performance of the three architectures.

Steps Followed
Dataset Preparation

Downloaded and organized the dataset into separate folders for each class.
Applied Image Augmentation using ImageDataGenerator to enhance generalization by applying techniques such as rotation, zoom, brightness adjustment, and flipping.
Split the dataset into training and validation sets.
Model Implementation

ResNet: Built a custom ResNet architecture with residual blocks and skip connections to prevent vanishing gradients.
Xception: Used the pre-trained Xception architecture with fine-tuning for the given dataset.
DenseNet: Leveraged the DenseNet model for its efficient feature propagation and reduced parameter requirements.
Training

Compiled models using the Adam optimizer with a learning rate of 0.001 and categorical cross-entropy loss.
Trained each model for 10 epochs, tracking validation accuracy and loss.
Adjusted steps_per_epoch and validation_steps dynamically based on the dataset size.
Evaluation

Evaluated each model on the validation set to compare performance metrics such as accuracy and loss.
Logged training histories for further analysis.
Dataset Link
FaceScrub Dataset

Results and Analysis
ResNet, Xception, and DenseNet were compared based on their validation accuracy and training efficiency.
Each architecture showcased its strengths, with ResNet providing stability, Xception excelling in feature extraction, and DenseNet ensuring efficient computation.

data set :
https://www.kaggle.com/datasets/rajnishe/facescrub-full
