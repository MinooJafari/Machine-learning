# Image Classification using Logistic Regression

## Project Description
This project demonstrates a basic image classification system using Machine Learning and Logistic Regression.

The main goal is to convert images into numerical arrays and train a Logistic Regression model to classify images into two categories (0 and 1).

The project introduces fundamental concepts of image processing, data preprocessing, feature extraction, and supervised machine learning using Python.

## Technologies and Libraries
- Python
- NumPy
- Pandas
- Matplotlib
- Seaborn
- Pillow (PIL)
- Scikit-learn

## Project Workflow

### 1. Image Loading
Images are loaded using the Pillow library.

### 2. Image to Array Conversion
Images are converted into NumPy arrays because machine learning algorithms work with numerical data rather than raw image files.

Each image has a size of 64 × 64 pixels and contains three color channels (RGB).

### 3. Feature Extraction
Only the Red (R) channel is extracted from each image to simplify the data.

The resulting 64 × 64 matrix is flattened into a one-dimensional array containing 4,096 features.

### 4. Data Normalization
Pixel values are divided by 255 to normalize them into a range between 0 and 1.

### 5. Dataset Preparation
A dataset containing 20 images is created.

Each image is represented by 4,096 numerical features, and labels (0 or 1) are assigned to the images.

### 6. Model Training
The dataset is divided into training and testing sets using `train_test_split`.

A Logistic Regression model is trained using Scikit-learn.

### 7. Model Evaluation
The trained model predicts the categories of test images.

Predictions are compared with the actual labels to identify correct and incorrect classifications.

### 8. New Image Prediction
A new image is loaded, converted into a NumPy array, preprocessed, and passed to the trained model for classification.

## Key Concepts Learned
- Image Processing with Pillow
- Converting Images into NumPy Arrays
- RGB Color Channels
- Pixel Value Extraction
- Image Flattening and Reshaping
- Data Normalization
- Feature Extraction
- Training and Testing Data
- Logistic Regression
- Image Classification
- Machine Learning Model Prediction

## Model
**Algorithm:** Logistic Regression

**Input Features:** 4,096 pixel values per image

**Image Dimensions:** 64 × 64 pixels

**Number of Images:** 20

**Classification Type:** Binary Classification (0 and 1)

## Project Structure

```text
Image-Classification/
│
├── dataset/
│   ├── 1.bmp
│   ├── 2.bmp
│   ├── ...
│   ├── 20.bmp
│   └── t2.bmp
│
├── Image_Classification.ipynb
│
└── README.md
```

## Future Improvements
- Increase the size of the training dataset.
- Use all three RGB channels instead of only the Red channel.
- Improve model performance through hyperparameter tuning.
- Evaluate the model using accuracy, precision, recall, and a confusion matrix.
- Experiment with other classification algorithms.

