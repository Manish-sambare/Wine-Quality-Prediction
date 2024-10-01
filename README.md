# Wine Quality Prediction 🍷

## Project Overview
This project aims to predict wine quality ratings based on physicochemical properties using a multiclass classification model. The dataset contains several chemical properties, and the target variable is a quality rating. The model leverages a Stochastic Gradient Descent (SGD) Classifier to classify wines into different quality categories.

## Dataset
- **Source**: [Wine Quality Dataset](https://archive.ics.uci.edu/ml/datasets/wine+quality)
- **Features**: 11 physicochemical properties such as acidity, pH, residual sugar, etc.
- **Target**: Quality rating ranging from 0 to 10.

## Workflow
### Data Preprocessing
- Handled missing values.
- Scaled the features using standardization for consistent input to the model.
- Split the dataset into training and testing sets using an 80-20 split.

### Model Training
- Utilized SGD Classifier for multiclass classification.
- Trained and validated the model using a train-test split.

### Evaluation
- Achieved an **accuracy of 85%**.
- Evaluated using confusion matrix and classification report.

## Key Libraries Used
- `pandas`, `numpy`
- `scikit-learn`
- `matplotlib`

## How to Run
1. Install the required libraries:
   ```bash
   pip install -r requirements.txt
   ```
2. Run the Jupyter notebook:
   - Open the `wineQT.ipynb` file and execute the cells sequentially.

## Results
The model successfully predicts wine quality with an accuracy of 85%, providing valuable insights into wine categorization based on chemical properties.
