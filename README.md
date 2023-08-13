# Mask_Detection
A Mask Detection project using Python.

### About
Masks play a crucial role in protecting the health of individuals against respiratory diseases, as is one of the few precautions available for COVID-19 in the absence of immunization. With this dataset, it is possible to create a model to detect people wearing masks, not wearing them, or wearing masks improperly.

### Dataset
The dataset contains 3 folders labeled as to which class they belong to. 
The 3 classes are-
1- "with_mask"
2- "without_mask"
3- "mask_weared_incorrect"

Each folder holds 2994 images of people that belong to such a labeled class.

### Python Libraries
1. os: The os library provides a way to interact with the operating system and perform tasks related to file handling, directory management, and more. It allows you to navigate and manipulate files, directories, and paths on your computer.

2- numpy: NumPy is a fundamental library for numerical computations in Python. It provides support for large, multi-dimensional arrays and matrices, along with a variety of mathematical functions to operate on these arrays efficiently.

3- matplotlib.pyplot: Matplotlib is a widely-used library for creating static, animated, and interactive visualizations in Python. The pyplot module provides an interface similar to MATLAB for generating plots and graphs.

4- tensorflow: TensorFlow is an open-source machine learning framework developed by Google. It provides a platform for building and training machine learning models, particularly deep learning models, using computational graphs.

5- keras: Keras is a high-level neural networks API that is designed to be user-friendly and intuitive. It can work on top of other deep learning frameworks, such as TensorFlow, and simplifies the process of building and training neural networks.

6- ImageDataGenerator: In the context of deep learning and image processing, ImageDataGenerator is a class in Keras that generates batches of augmented data from a directory of images. It's commonly used to prepare data for training deep learning models.

7- MobileNetV2: MobileNetV2 is a deep learning architecture designed for mobile and embedded vision applications. It's known for its efficiency and is commonly used for image classification and feature extraction tasks.

8- Input: In Keras, the Input class is used to create an input tensor for a neural network model. It defines the shape and data type of the input data.

9- AveragePooling2D: AveragePooling2D is a layer in deep neural networks that performs average pooling, a technique used to downsample the spatial dimensions of an image while retaining important features.

10- FlattenDense: These terms likely refer to layers in a neural network model. Flatten is used to convert multi-dimensional data into a one-dimensional vector, and Dense is a fully connected layer where each neuron is connected to every neuron in the previous layer.

11- Dropout: Dropout is a regularization technique commonly used in neural networks to prevent overfitting. It randomly drops a fraction of neurons during training, reducing their reliance on specific neurons and enhancing generalization.

12- Model: In Keras, a Model is a class that represents a neural network model. It can be used to define and compile a model architecture, as well as train and evaluate it.

13- Adam: Adam is an optimization algorithm commonly used to update the parameters of neural network models during training. It adapts the learning rate based on the past gradients and momentums.

14- sklearn: Scikit-learn is a machine learning library for Python. It provides simple and efficient tools for data mining and data analysis, including various algorithms for classification, regression, clustering, and more.

15- classification_report: In scikit-learn, the classification_report function generates a comprehensive report on the performance of a classification model. It includes metrics such as precision, recall, F1-score, and support for each class.

16- train_test_split: This is a function from scikit-learn that helps in splitting a dataset into training and testing subsets. It's a common step in machine learning workflows to evaluate the model's performance on unseen data.
