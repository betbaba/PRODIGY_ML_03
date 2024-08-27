## Dataset Information

### Where to Find the Dataset
For this project, I utilized a dataset from the Kaggle website. You can access and download the dataset directly from Kaggle using the following link:[Dataset]( https://www.kaggle.com/c/dogs-vs-cats/data)


### Dataset Details
Due to the performance limitations of my laptop, I selected 2000 images of cats and 2000 images of dogs from the dataset to train the model. If you have a more powerful machine, you are encouraged to use the entire dataset for potentially better results.

### Dataset Folder Structure
The dataset is organized into the following folder structure, which is crucial for the training process:

```
dataset
├── test1
└── train
    ├── cat
    └── dog
```

- **train**: This directory contains the training images, divided into two subdirectories: `cat` for cat images and `dog` for dog images.
- **test1**: This directory is used for testing purposes and should contain the images you intend to use to evaluate the model.

Make sure to place your training and testing datasets in the appropriate directories as shown above before starting the model training process.
