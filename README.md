# Employee Attrition Risk Analysis

This repository contains the analysis of factors contributing to employee attrition. It uses machine learning models to predict the likelihood of employees leaving an organization and calculates an attrition risk score.

## Project Structure

- `attrition_risk_analysis.ipynb`: Jupyter notebook containing the analysis and model training.
- `WA_Fn-UseC_-HR-Employee-Attrition.csv`: Dataset used for the analysis.
- `requirements.txt`: List of Python packages required to run the notebook.

## Getting Started

### Prerequisites

- Python 3.6+
- pip (Python package installer)

### Installation

1. Clone this repository to your local machine using the following command:

    ```
    git clone https://github.com/FlamingoCalves/attrition-risk-score.git
    cd <your-repo-name>
    ```

2. Install the required packages using:

    ```
    pip install -r requirements.txt
    ```

### Running the Analysis

To run the analysis, open the `attrition_risk_analysis.ipynb` notebook in a Jupyter environment. You can use the following command if you have Jupyter installed:

    ```
    jupyter notebook attrition_risk_analysis.ipynb
    ```

Alternatively, you can use JupyterLab:

    ```
    jupyter lab attrition_risk_analysis.ipynb
    ```

Once the notebook is open, you can run each cell sequentially to see the analysis, model training, and risk score calculation.

## Dataset

The dataset `WA_Fn-UseC_-HR-Employee-Attrition.csv` contains various attributes of employees along with an indicator of whether the employee left the company (Attrition).

## Notebooks

The `attrition_risk_analysis.ipynb` notebook walks through data preprocessing, exploratory data analysis, feature engineering, model training (Logistic Regression and Random Forest), and risk score calculation.