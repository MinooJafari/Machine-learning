# Handwritten Digit Recognition

## Project Overview
This project focuses on recognizing handwritten digits using Machine Learning. It uses the **Digits Dataset** provided by Scikit-learn and applies a Logistic Regression model to classify handwritten numbers from 0 to 9.

The model analyzes 8×8 pixel images and predicts which digit each image represents.

## Dataset
The project uses the built-in Scikit-learn Digits Dataset.

- **Total samples:** 1,797 handwritten digit images
- **Image size:** 8×8 pixels
- **Features:** 64 pixel values per image
- **Target classes:** 10 (digits 0–9)
- **Pixel intensity range:** 0–16

## Technologies & Libraries
- Python
- NumPy
- Pandas
- Matplotlib
- Seaborn
- Scikit-learn
- Logistic Regression

## Project Workflow

1. **Data Loading:** Imported the Digits Dataset using Scikit-learn.
2. **Data Exploration:** Examined the dataset, image dimensions, features, and target labels.
3. **Data Visualization:** Displayed handwritten digit images using Matplotlib.
4. **Data Splitting:** Divided the dataset into training (80%) and testing (20%) sets.
5. **Model Training:** Trained a Logistic Regression classification model.
6. **Prediction:** Used the trained model to predict handwritten digits in the test dataset.
7. **Evaluation:** Compared predicted values with actual labels and calculated the model's accuracy.

## Model Performance

The model was evaluated on 360 test samples.

| Metric | Result |
|---|---:|
| Total test samples | 360 |
| Correct predictions | 351 |
| Incorrect predictions | 9 |
| Accuracy | **97.5%** |

The model achieved an accuracy of **97.5%**, demonstrating strong performance in handwritten digit classification.

## Key Concepts Learned
- Understanding image datasets
- Feature extraction and pixel-based data representation
- Data preprocessing and train-test splitting
- Logistic Regression
- Multi-class classification
- Model prediction and evaluation
- Calculating classification accuracy

## How to Run

1. Clone this repository:

```bash
git clone https://github.com/your-username/your-repository.git
```

2. Install the required libraries:

```bash
pip install numpy pandas matplotlib seaborn scikit-learn
```

3. Open the Jupyter Notebook:

```bash
jupyter notebook
```

4. Run the notebook cells to train the model and evaluate its predictions.

## Conclusion

This project demonstrates how Machine Learning can be used for image classification and handwritten digit recognition.

By applying Logistic Regression to the Scikit-learn Digits Dataset, the model achieved **97.5% accuracy** on the test set.

This project was developed as part of my journey in learning Python, Machine Learning, and Data Science.
