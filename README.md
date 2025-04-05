# Titanic Dataset Survival Prediction

### Link to notebook: [model.ipynb](https://github.com/bncodes19/applied-ml-bneely/blob/main/lab03/ml03_neely.ipynb)

## Overview
In this lab, the Mushroom dataset from UC-Irvine Machine Learning Repository is analyzed.

Three types of models are employed for predicting the poisonous of a mushroom:
- Random Forest: designed to create a collection of decision trees to improve accuracy
- Support Vector Machine: designed to find the "best boundary" (aka a Hyperplane) that separates data into classes. This model works well with complex data and small datasets


## Sections of the analysis:
- Section 1: Import the Dataset
- Section 2: Data Exploration and Preparation
   - 2.1: Explore Data Patterns and Distributions
   - 2.2: Feature Engineering
- Section 3: Feature Selection and Justification
   - 3.1: Choose Features and Target
- Section 4: Train a Model (Random Forest)
   - 4.1 Split the data
   - 4.2 Train trhe model
   - 4.3 Evaluate performance
- Section 5: Compare Alternative Model
   - 5.1 Support Vector Machine
- Section 6: Final Thoughts and Insights

## Dataset 
Titanic dataset
- We use the built-in dataset from UC Irvine Machine Learning Repository:
<https://archive.ics.uci.edu/dataset/73/mushroom>

## Python Library for Machine Learning: scikit-learn
We use scikit-learn, built on NumPy, SciPy, and matplotlib
   - Read more at <https://scikit-learn.org/>
   - Scikit-learn supports classification, regression, and clustering.
   - This project applies regression.

**Important:** Use a 2-step installation to avoid timeouts and partial installs:  
1. **First Install:** Install from `requirements.txt` with `scikit-learn` commented out.  
2. **Second Install:** Uncomment `scikit-learn` and rerun the install command.

---

## How to clone this project for further development:
Clone this repository:  
```shell
git clone <https://github.com/bncodes19/ml-classification-neely/tree/main>
```
### To set up the virtual environment in the terminal:
``` shell
python3 -m venv .venv
```
4. Activate the virtual enivronment
``` shell
source .venv/bin/activate
```