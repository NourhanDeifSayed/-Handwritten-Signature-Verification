# -Handwritten-Signature-Verification
signature verification model using a Siamese Neural Network (SNN) architecture. The model is designed to distinguish between real and forged handwritten signatures. The main steps include:

Dataset Setup:

The dataset is downloaded from Kaggle, containing real and forged signature images.
The images are organized into Train and Test directories with separate subdirectories for real and forged signatures.
Data Preprocessing:

Image augmentation techniques like rotation, shifting, zooming, and flipping are applied to the training data to improve model generalization.
The pixel values are rescaled to a range of 0 to 1.
Model Architecture:

A shared convolutional neural network (CNN) is used for both input branches (real and forged images).
The embeddings from both branches are compared using L1 distance to determine if the signatures belong to the same class.
Training and Evaluation:

The model is trained using binary cross-entropy loss and Adam optimizer.
Early stopping is employed to prevent overfitting during training.
After training, the model is evaluated on a test set with metrics like accuracy and loss.
Output:

The model is capable of classifying pairs of images as real or fake signatures, showing strong potential for real-world application in signature verification tasks.

