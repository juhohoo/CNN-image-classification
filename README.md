# CNN-image-classification
Convolutional Neural Network for image classification. Deep Learning course 2023. Credits to Lauri Vuorenkoski and Juho Hotari.

Training data consists of 20,000 RGB images with size 128x128 pixels and 14 different classes. Data is available here: https://www.cs.helsinki.fi/u/yangarbe/Courses/2023-deep-learning/image-training-corpus+annotations/

Repository includes a Notebook. CNN has four convolutional layers including maxpooling and followed by fully connected linear layers. Code introduces different performance metrics, such as loss, sensitivity, specificity and F1-score. Data augmentation is done by randomly rotating the training images. The CNN model reaches 0.99 training accuracy and 0.92 validation accuracy. Additional test set of 5000 new images is used at the end.
