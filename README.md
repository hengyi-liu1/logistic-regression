# Logistic Regression for Diagnosing Temporal Lobe Epilepsy (TLE)

This project implements a logistic regression classifier **from scratch** to diagnose Temporal Lobe Epilepsy (TLE) using brain structure measurements. The model is trained and evaluated on neuroimaging-derived features, with performance comparable to scikit-learn’s implementation.

## Highlights

- Implemented logistic regression from scratch using NumPy
- Achieved comparable train/test accuracy to scikit-learn
- Applied regularization and grid search for hyperparameter tuning
- Implemented stochastic gradient descent to improve computational efficiency
- Built reusable training and evaluation pipelines

## Methods & Results

### Data Exploration

- Visualized hippocampus and caudate nucleus surface areas
- Found hippocampus measurements to be more discriminative for TLE classification

### Model Training

- Logistic regression trained on hippocampus features achieved ~80% test accuracy
- SGD-based training on less separable caudate data achieved ~60% test accuracy
- Regularization helped mitigate overfitting across experiments

## Technical Skills

- Python, NumPy, Matplotlib
- Logistic regression (from scratch)
- Stochastic Gradient Descent (SGD)
- Regularization techniques
- Hyperparameter tuning (Grid Search)
- Model evaluation and visualization

## Repository Contents

- `logistic_regression.ipynb` – Implementation, experiments, and visualizations

## Running the Project

1. Clone the repository:
   ```bash
   git clone https://github.com/hengyi-liu1/logistic-regression.git
   ```
2. Open `logistic_regression.ipynb` in Jupyter Notebook or VS Code
3. Install dependencies:
   ```bash
   pip install -r requirements.txt
   ```
4. Run all cells to reproduce results