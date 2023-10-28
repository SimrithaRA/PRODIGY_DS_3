---

# Decision Tree Classifier for Customer Purchase Prediction

This repository contains a Python script that demonstrates how to build a decision tree classifier to predict whether a customer will purchase a product or service based on their demographic and behavioral data. The dataset used in this example is the Bank Marketing dataset from the UCI Machine Learning Repository.

## Getting Started

These instructions will help you set up and run the decision tree classifier code on your local machine.

### Prerequisites

To run the code, you will need the following libraries and tools installed:

- Python 3
- Jupyter Notebook or any Python IDE of your choice
- Required Python libraries (install using `pip`):
  - pandas
  - numpy
  - scikit-learn (sklearn)
  - graphviz

### Installation

1. Clone this repository to your local machine:

   ```bash
   git clone https://github.com/yourusername/decision-tree-customer-prediction.git
   ```

2. Navigate to the project directory:

   ```bash
   cd decision-tree-customer-prediction
   ```

3. Ensure you have the necessary prerequisites installed.

## Usage

1. Open a Jupyter Notebook or your preferred Python IDE.
2. Load and run the Python script provided in the repository to build and evaluate the decision tree classifier. The script is named `decision_tree_classifier.ipynb`.

The script performs the following steps:

- Loads the Bank Marketing dataset.
- Preprocesses the data, including label encoding categorical variables.
- Splits the data into training and test sets.
- Builds a decision tree classifier with different depths and evaluates its accuracy on both the training and test sets.
- Visualizes the decision tree using Graphviz.

---
