# Overview 
Bangla is a rich language with a variety of characters,
which includes numerals, basic characters, compound, and
modifier characters. This makes it more challenging to recognize
handwritten characters in Bangla than in other languages. Pretrained convolutional neural network (CNN) architectures are
effective because they can learn complex features from images,
which is significant considering variations in handwriting styles.
This work involves using an ensemble model consisting of pre-trained CNN
architectures to classify compound bangla
handwritten characters. The ensemble model comprises four pretrained convolutional neural network architectures - ResNet50,
DenseNet121, Xception, and EfficientNetB0. The model
is trained on MatrrivaSha dataset. To keep each image in the dataset noise-free, they are
all preprocessed using a bilateral filter. The image size is reduced
to 75X75 pixels, which has been used as input in several CNN
architectures. Due to the limitations of RAM and GPU, the datasets are divided into subsets during model train and test.

# Requirements

*   Python
*   Numpy
*   Tensorflow
*   Keras
*   OpenCV
*   Pandas
*   Seaborn
*   Matplotlib

# Dataset
MatriVasha: Bangla Handwritten Compound Character Dataset and Recognition (https://data.mendeley.com/datasets/v39pc2g2wp/1)
