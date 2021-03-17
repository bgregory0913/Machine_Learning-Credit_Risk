<h3 align="center">About The Project:</h3>
<p align="center">
  <a href="https://github.com/bgregory0913/Machine_Learning-Credit_Risk">
    <img src="Images/CreditRisk.jpg" alt="CreditRisk" align="center">
  </a>
</p>

### Project Overview:
_This project is an example of using various samplers and ensemble samplers to mitigate risk for a Peer-to-Peer Lending Service._

Peer-to-peer Lending Services let investors loan people money without using a bank. In this case, the Lending Service wants more false positives than false negatives, and equal amounts of true positives and true negatives to determine the risk of lending money without return.

__We will predict credit risk with the following Machine Learning models:__
1. Logistic Regression
2. Over-Sampling
    * Naive Random Over-Sampling
    * SMOTE Over-Sampling
3. Under-Sampling
    * Cluster Centroids
4. Combination Sampling (Over and Under)
    * SMOTEENN - Combine over and under sampling using SMOTE and Edited Nearest Neighbors (EEN).
    
__We will analyze each model's performance by:__
1. Calculating the Balanced Accuracy Score
2. Viewing the Confusion Matrix
3. Generating and Analyzing an Imbalanced Classication Report

### Built With:

This project is written in Python using Jupyter Notebook and the Imbalanced-Learn and ScKit-Learn Python modules.

* [Python](https://www.python.org/)
* [JupyterNotebook](https://jupyter.org/)
* [Imbalanced-Learn](https://imbalanced-learn.org)
* [SciKit-Learn](https://scikit-learn.org)

## To get a local copy up and running, follow the steps below.

### Prerequisites:

Download and install [JupyterNotebook](https://jupyter.org/) to execute the .ipynb files.

### Installation:

1. Clone the repo
   * git clone https://github.com/bgregory0913/Machine_Learning-Credit_Risk
2. Install python modules:
   * pip install imblearn
   * pip install sklean

## Contact:

Blake Gregory - [LinkedIn](www.linkedin.com/in/blake-greg) - blake.gregory@tilineum.com

