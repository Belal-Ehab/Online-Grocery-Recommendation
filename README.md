# Online Grocery Recommendation System

This project builds a classification model to recommend groceries based on users' past purchases using the Instacart Market Basket Analysis dataset.

## Objective

- Understand and clean the dataset.
- Build classification models to predict product reordering.
- Evaluate models using accuracy, precision, recall, and AUC-ROC.
- Optimize models through hyperparameter tuning.

## Dataset

The dataset is available on Kaggle: Instacart Market Basket Analysis: https://www.kaggle.com/datasets/yasserh/instacart-online-grocery-basket-analysis-dataset . It includes:

- `aisles.csv`: Aisle IDs and names.
- `departments.csv`: Department IDs and names.
- `orders.csv`: Order details (user ID, order ID, etc.).
- `products.csv`: Product details.
- `order_products__prior.csv`: Products in prior orders.
- `order_products__train.csv`: Products in training orders.

**Note**: Dataset files are not included in this repository. Download them from the Kaggle link above.

## Files

- `Online Grocery Recommendation System.ipynb`: Jupyter notebook containing data loading, preprocessing, and initial analysis.

## Setup

1. Install dependencies:

   ```bash
   pip install pandas numpy scikit-learn matplotlib seaborn
   ```
2. Download the dataset from Kaggle.
3. Open `Online Grocery Recommendation System.ipynb` in Jupyter Notebook to run or explore the code.
