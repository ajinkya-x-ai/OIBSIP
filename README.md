# Iris Flower Classification

## OIBSIP — Data Science Task 1

This project uses the classic Iris dataset from **scikit-learn** to classify iris flowers into:

- Setosa
- Versicolor
- Virginica

### Objective

Train and compare multiple machine-learning classification models using iris flower measurements.

### Dataset

The Iris dataset contains **150 samples** and four input features:

- Sepal length
- Sepal width
- Petal length
- Petal width

The dataset is loaded directly from `sklearn.datasets`, so no external dataset download is required.

### Models Used

1. Logistic Regression
2. K-Nearest Neighbors (KNN)
3. Decision Tree
4. Random Forest

### Workflow

1. Import the required Python libraries.
2. Load and inspect the Iris dataset.
3. Perform exploratory data analysis.
4. Check data types, missing values, descriptive statistics, and class distribution.
5. Visualize relationships between features.
6. Split the data into training and testing sets.
7. Standardize the input features.
8. Train four classification models.
9. Evaluate the models using accuracy, confusion matrices, precision, recall, and F1-score.
10. Select the best-performing model.

### Results

On the test set used in the notebook:

| Model | Accuracy |
|---|---:|
| Logistic Regression | 93.33% |
| K-Nearest Neighbors | 93.33% |
| Decision Tree | 93.33% |
| Random Forest | 90.00% |

**Best-performing model:** Logistic Regression, with **93.33% test accuracy**.  
(KNN and Decision Tree achieved the same accuracy on this particular train/test split.)

### Key Finding

Petal length and petal width are the most discriminative features for separating the three Iris species, although all four features are used for model training.

### Files

- `Iris_Flower_Classification.ipynb` — complete analysis, visualizations, model training, and evaluation.
- `outputs/` — exported visual outputs from the notebook.
- `requirements.txt` — Python packages needed to run the project.

### How to Run

```bash
pip install -r requirements.txt
jupyter notebook Iris_Flower_Classification.ipynb
```

Run all notebook cells from top to bottom.

## Demo Video

For the OIBSIP demo video, begin with a **2-second static title card** showing:

- Your Full Name
- Assigned Track
- Task Title: Iris Flower Classification

Then demonstrate the completed notebook/project functioning end-to-end.

## Author

Replace this line with your name before submitting.
