# Image Classifier using TensorFlow and Keras
## Overview
This project serves as an illustrative example of constructing an image classifier through deep learning techniques. The primary objective is to develop a model capable of distinguishing whether an input image depicts a dog or a cat.

## Data
The data comprises images of dogs and cats, conveniently stored in two zip files within the repository: data/raw/train.zip and data/raw/test1.zip. These images are categorized into two names: dogs and cats.

To optimize loading time and prioritize programming efficiency over model effectiveness, all images have been resized to 10% of their original dimensions. Git LFS is employed to manage file storage in the repository.

## Files
The project includes two main notebooks:

DATA_INGESTION.ipynb: This notebook imports images from the zip files and organizes them into dog and cat folders. It also displays 9 of each sort in the notebook to visualize them.

ML_DEVELOP.ipynb: This notebook focuses on model development using TensorFlow and Keras. It loads data from data/interim/ , splits it into training and testing sets, constructs a Convolutional Neural Network (CNN), and trains it on the training set. The notebook concludes by loading a dog image and predicting its label using the trained model.

## Execution
To run this project, ensure you have Python 3, TensorFlow, Keras, pandas, numpy, matplotlib, and PIL installed. Additionally, enable Git LFS on your GitHub account.

To execute the notebooks, you can use Jupyter Notebook or Google Colab. Clone the repository and unzip the cat.zip and dog.zip files in the same folder as the notebooks. Afterward, open the notebooks and execute the cells in sequence.