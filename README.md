# DSIF_Final
A project containing a workflow for the modelling of loan classification.

* [About](#about)
* [Project Structure](#project-structure)
* [Getting Started](#getting-started)
    * [Prerequisites](#prerequisites)
* [Components](#components)
    * [Data Cleaning and EDA](#data-cleaning-and-eda)
    * [Baseline Model](#baseline-model)
    * [Challenger Model](#challenger-model)

## About
This project aims to build a predictive model that can automatically classify loan applications, helping financial institutions streamline their decision-making process. The repository includes the steps taken from initial data understanding to the development and comparison of different classification models.

## Project Structure
loan_application_classification/
├── notebooks/
│   ├── Data Preparation and Cleaning.ipynb     # Notebook for data cleaning.
│   ├── EDA and preparation for modelling.ipynb # Notebook for EDA.
│   ├── Baseline Model.ipynb        # Notebook implementing the baseline classification model.
│   ├── Challenger Model.ipynb      # Notebook implementing the challenger classification model.
│   └── Pushing to Git.inpyb        # Notebook implementing push to Git
├── data/                         # Directory to store the dataset (e.g., loan_data.csv).
├── reports/                      # Directory for generated reports and visualizations (optional)..
└── README.md                     # This file.

## Getting Started

Follow these instructions to set up and explore the project.

### Prerequisites

Ensure you have the following installed:

* **Python** (version 3.8 or higher is recommended)
* **pip** (Python package installer)
* **Jupyter Notebook**

You can install Jupyter Notebook using pip:

```bash
pip install notebook
```

## Components
This project is primarily implemented through Jupyter Notebooks.

### Data Cleaning and EDA
* Navigate to the notebooks/ directory.
* Open and run the ```data_cleaning_eda.ipynb notebook```. This notebook contains the steps for:
* Loading and inspecting the dataset.
* Handling missing values.
* Addressing outliers.
* Performing exploratory data analysis to understand the data distribution and relationships between features.
* Feature engineering.
  
### Baseline Model
* Open and run the ```baseline_model.ipynb notebook```. This notebook implements a basic classification model (e.g., Logistic Regression, Decision Tree) to establish a preliminary performance benchmark. It typically includes:
* Feature scaling and encoding.
* Splitting the data into training and testing sets.
* Training the baseline model.
* Evaluating the model's performance using relevant metrics (e.g., accuracy, precision, recall, F1-score).

### Challenger Model
* Open and run the ```challenger_model.ipynb``` notebook. This notebook implements a more advanced or alternative classification model (e.g., Random Forest, Gradient Boosting, Neural Network) that aims to improve upon the baseline model's performance. It may involve:
* Trying different algorithms.
* Hyperparameter tuning.
* More sophisticated feature engineering or selection techniques.
* Detailed performance evaluation and comparison with the baseline model.

