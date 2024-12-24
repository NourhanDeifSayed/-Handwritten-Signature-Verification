# -Handwritten-Signature-Verification
Signature Verification using Siamese Network and CNN

This project involves building a signature verification system using a Siamese Neural Network (SNN) combined with Convolutional Neural Networks (CNN). The system is designed to distinguish between real and forged signatures. The model architecture includes:

Pretrained CNN for feature extraction followed by custom CNN layers with Batch Normalization, MaxPooling, and Dropout to enhance generalization and accuracy.
Siamese architecture utilizing L1 distance to compare pairs of signatures.
Image augmentation techniques to improve model robustness and generalization.
Achieved high accuracy in signature verification tasks by training with a binary cross-entropy loss function and Adam optimizer.
Technologies used: TensorFlow, Keras, Python, Siamese Networks, Convolutional Neural Networks (CNNs), Batch Normalization, MaxPooling, Image Augmentation.
