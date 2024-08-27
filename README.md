
# Task-03: Cat and Dog Image Classification Using Support Vector Machine (SVM)

## Project Overview
This project involves implementing a Support Vector Machine (SVM) to classify images of cats and dogs. The goal is to accurately distinguish between cat and dog images using the SVM algorithm, leveraging the dataset provided by Kaggle.

## Dataset Information

### Source
The dataset used for this project is sourced from Kaggle and can be accessed through the following link:

**[Kaggle Dataset - Dogs vs. Cats](https://www.kaggle.com/c/dogs-vs-cats/data)**

### Dataset Structure
The dataset comprises images of cats and dogs, which are organized into separate directories for training and testing purposes. The typical structure is as follows:

```
dataset
├── test1
└── train
    ├── cat
    └── dog
```

- **train**: Contains the training images, with separate subdirectories for cat and dog images.
- **test1**: Contains the images used for testing the model's performance.

## Model Implementation

### Support Vector Machine (SVM)
Support Vector Machine (SVM) is a supervised machine learning algorithm that can be used for classification tasks. In this project, SVM is implemented to classify the images of cats and dogs based on the features extracted from the images.

### Key Steps:
1. **Data Preprocessing**:
   - Images are resized, normalized, and converted into a format suitable for SVM training.
   
2. **Feature Extraction**:
   - Relevant features from the images are extracted to feed into the SVM model.

3. **Model Training**:
   - The SVM model is trained using the preprocessed and feature-extracted training dataset.

4. **Model Evaluation**:
   - The trained model is evaluated using the test dataset to assess its accuracy and performance in classifying the images.

### Requirements

- Python 3.x
- Scikit-learn
- NumPy
- OpenCV (for image processing)
- Jupyter Notebook (recommended for running the code)

### How to Run

1. **Install the necessary libraries**:
   ```bash
   pip install scikit-learn numpy opencv-python
   ```

2. **Download and set up the dataset**:
   - Download the dataset from Kaggle and place it in the directory structure mentioned above.

3. **Run the Jupyter Notebook**:
   - Open the Jupyter Notebook file included in this project and execute the cells to preprocess the data, train the SVM model, and evaluate its performance.

## Conclusion
The implementation of SVM in this project provides a foundation for image classification tasks, specifically in distinguishing between cats and dogs. The results and accuracy of the model depend on the quality of the dataset and the preprocessing techniques applied.
