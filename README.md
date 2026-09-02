# Predictive Modeling

[![Python](https://img.shields.io/badge/Python-3.x-3776AB?logo=python&logoColor=white)](https://www.python.org/)
[![Jupyter](https://img.shields.io/badge/Jupyter-Notebooks-F37626?logo=jupyter&logoColor=white)](https://jupyter.org/)
[![License](https://img.shields.io/badge/license-not%20specified-lightgrey)](#license)

A collection of end-to-end predictive modeling notebooks covering **time-series forecasting** and **healthcare classification**. The projects move from exploratory analysis and feature engineering to model evaluation, with practical examples involving sales, heart disease, and heart-failure risk.

## Projects

| Notebook | Problem | Highlights |
| --- | --- | --- |
| [Complete Guide on Time-Series Analysis](complete-guide-on-time-series-analysis-in-python.ipynb) | Time-series analysis | A broad walkthrough of exploring, decomposing, and modeling temporal data in Python. |
| [Sales Forecasting: Fighting Data Leakage](sales-forecasting-fighting-data-leakage.ipynb) | Sales forecasting | Demonstrates how leakage can produce misleading results and how to build a more realistic forecasting workflow. |
| [Sales Forecasting with SARIMA & Prophet](sales-forecasting-with-sarima-prophet.ipynb) | Sales forecasting | Compares statistical and additive forecasting approaches for future sales. |
| [Sales Forecasting with SARIMA & Prophet — alternate version](sales_forecasting_with_sarima_prophet.ipynb) | Sales forecasting | An alternate iteration of the SARIMA and Prophet analysis. |
| [Heart Disease Prediction](heart-disease-prediction.ipynb) | Binary classification | Explores patient health indicators and trains models to identify potential heart disease, emphasizing recall for the positive class. |
| [Heart Failure Prediction: 5 Models](heart-failure-prediction-cv-score-90-5-models.ipynb) | Binary classification | Compares five classification models using cross-validation and model-performance metrics. |

## What You'll Find

- Exploratory data analysis and visualization
- Data cleaning and preprocessing
- Feature engineering for tabular and time-series data
- Leakage-aware validation
- Classification and forecasting model comparisons
- Evaluation with task-appropriate metrics

## Getting Started

### 1. Clone the repository

```bash
git clone https://github.com/JCZY999/Predictive_Modeling.git
cd Predictive_Modeling
```

### 2. Create a virtual environment

```bash
python -m venv .venv
```

Activate it:

```bash
# macOS / Linux
source .venv/bin/activate

# Windows (PowerShell)
.venv\Scripts\Activate.ps1
```

### 3. Install Jupyter and the analysis libraries

The exact libraries vary by notebook. A practical starting environment is:

```bash
python -m pip install --upgrade pip
pip install jupyter pandas numpy matplotlib seaborn scikit-learn statsmodels xgboost prophet
```

If a notebook imports an additional package, install it when prompted. Some notebooks may also expect datasets from their original public sources; check the opening cells and notes before running the analysis.

### 4. Launch Jupyter

```bash
jupyter notebook
```

Open a notebook from the file browser and run its cells from top to bottom. For the most reproducible results, restart the kernel before a full run.

## Suggested Learning Path

If you are new to predictive modeling, a useful order is:

1. Start with the [complete time-series guide](complete-guide-on-time-series-analysis-in-python.ipynb).
2. See why evaluation design matters in [Fighting Data Leakage](sales-forecasting-fighting-data-leakage.ipynb).
3. Compare forecasting techniques in [SARIMA & Prophet](sales-forecasting-with-sarima-prophet.ipynb).
4. Move to classification with [Heart Disease Prediction](heart-disease-prediction.ipynb).
5. Finish with the [five-model heart-failure comparison](heart-failure-prediction-cv-score-90-5-models.ipynb).

## Repository Structure

```text
Predictive_Modeling/
├── complete-guide-on-time-series-analysis-in-python.ipynb
├── heart-disease-prediction.ipynb
├── heart-failure-prediction-cv-score-90-5-models.ipynb
├── sales-forecasting-fighting-data-leakage.ipynb
├── sales-forecasting-with-sarima-prophet.ipynb
├── sales_forecasting_with_sarima_prophet.ipynb
└── README.md
```

## Contributing

Contributions are welcome. If you would like to improve an analysis, fix a notebook, or add a new predictive modeling example:

1. Fork the repository.
2. Create a feature branch.
3. Keep notebook outputs focused and remove sensitive or unnecessary data.
4. Open a pull request describing the change and how you validated it.

## License

No license has been specified yet. Until one is added, the repository remains under the copyright of its owner and should not be assumed to permit reuse or redistribution.

