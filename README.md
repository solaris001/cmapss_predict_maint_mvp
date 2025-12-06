# Predictive Maintenance using NASA CMAPSS Dataset

A comprehensive predictive maintenance project focused on turbofan engine degradation analysis and Remaining Useful Life (RUL) prediction using the [NASA C-MAPSS (Commercial Modular Aero-Propulsion System Simulation)](https://data.nasa.gov/dataset/cmapss-jet-engine-simulated-data) dataset.

## Project Overview

This project develops machine learning models to predict when turbofan engines will fail, enabling proactive maintenance scheduling and reducing operational downtime.

## Use Cases

### 1. RUL Regression
Predict the exact number of remaining operational cycles before engine failure as a continuous value.

### 2. Binary Classification
Classify engines into two categories: those requiring immediate maintenance (within a defined threshold) and those that can continue operating safely.

## Dataset

The NASA C-MAPSS dataset contains run-to-failure simulations of turbofan engines under various operating conditions:

- **4 sub-datasets** (FD001-FD004) with varying complexity
- **21 sensor measurements** per operational cycle
- **3 operational settings** (altitude, throttle, etc.)
- **Multiple fault modes** and operating conditions
- Time-series data from engine start until failure

Each dataset varies in the number of operating conditions (1 or 6) and fault modes (1 or 2), providing different levels of complexity for model development.

## Project Differentiation

Unlike many existing CMAPSS projects that focus solely on deep learning approaches or single models, this project:

- Covers the **complete ML pipeline** from EDA to deployment considerations
- Implements **both regression and classification** use cases
- Emphasizes **practical engineering** aspects (data quality, feature engineering, model interpretability)
- Provides **comprehensive documentation** of decisions and trade-offs
- Focuses on **reproducibility and best practices**

## Project Phases

1. **Exploratory Data Analysis (EDA)** - Understanding data patterns, sensor behaviors, and degradation trends
2. **Data Preprocessing** - Handling data quality issues, feature engineering, and normalization
3. **Model Development** - Building and training predictive models for both use cases
4. **Model Evaluation** - Performance assessment using appropriate metrics
5. **Model Interpretation** - Understanding model decisions and feature importance
6. **Documentation** - Comprehensive project documentation and findings

## Tech Stack

### Core Libraries
- **Python 3.x**
- **Pandas** - Data manipulation and analysis
- **NumPy** - Numerical computing
- **Scikit-learn** - Machine learning models and preprocessing
- **Matplotlib & Seaborn** - Data visualization

### Additional Tools
- **Jupyter Notebook** - Interactive development and documentation
- **Git** - Version control

### Planned Extensions
- Deep learning frameworks (TensorFlow/PyTorch) for advanced models
- MLflow for experiment tracking
- Docker for reproducible environments
- C# & .NET - Backend service development
- API integration - RESTful API for model serving and predictions


## Getting Started

*Coming soon - Setup instructions and quickstart guide*

## Project Structure

*Coming soon - Detailed directory structure and file descriptions*

## License

*To be determined*

## References

- Saxena, A., & Goebel, K. (2008). Turbofan Engine Degradation Simulation Data Set. NASA Prognostics Data Repository, NASA Ames Research Center, Moffett Field, CA. 
- Download the dataset at: [NASA PCoE Data Repository](https://www.nasa.gov/intelligent-systems-division/discovery-and-systems-health/pcoe/pcoe-data-set-repository/)
