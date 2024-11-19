# NASA-Near-Earth-Object-Analysis

## Overview

This project analyzes NASA's Near-Earth Object (NEO) data to explore trends, patterns, and risks associated with objects approaching Earth's orbit. It integrates advanced data science techniques, machine learning models, and interactive visualizations to study NEO characteristics and potential threats.

## Key Features

1. **Data Exploration**
   - Explore detailed NEO metrics such as size, velocity, and approach distance.
   - Analyze time-series data to observe close approaches over time.

2. **Visualization**
   - Scatter plots, histograms, and heatmaps for understanding data distributions.
   - Interactive 3D scatter plots for clustering insights.

3. **Clustering and Risk Analysis**
   - Use K-Means and HDBSCAN for clustering NEOs based on orbital and size parameters.
   - Identify high-risk NEOs based on proximity and size.

4. **Predictive Modeling**
   - Build and evaluate machine learning models (e.g., KNN and XGBoost).
   - Classify NEOs for potential hazards.

## Dataset

The dataset contains detailed attributes of near-Earth objects, including:
- Object diameter
- Approach distance
- Velocity
- Orbital parameters
- Classification of hazard levels

## Notebook Structure

### Titles
- **Introduction and Objective**: Overview of the analysis goals.
- **Dataset Overview**: Description of the NASA NEO dataset.
- **Exploratory Data Analysis (EDA)**:
  - Visualizations: Scatter plots, histograms, and heatmaps.
  - Time-series trends of close approaches.
- **Clustering**:
  - Techniques: K-Means, HDBSCAN.
  - 3D visualizations of clusters.
  - Silhouette scoring for evaluation.
- **Predictive Modeling**:
  - Models: KNN, XGBoost.
  - Risk analysis and classification.
- **Interactive Visualizations**:
  - Use Plotly for engaging visual outputs.

### Highlights from Code Comments
- Core libraries for data manipulation: `pandas`, `numpy`, `matplotlib`, `seaborn`.
- Advanced clustering methods such as `HDBSCAN` and K-Means.
- Descriptive statistics and missing value handling.
- 3D scatter plotting for cluster visualization using `matplotlib` and `plotly`.
- Predictive modeling with hyperparameter tuning using `XGBoost` and `KNN`.

## Installation

1. Clone this repository:
   ```bash
   git clone https://github.com/your-username/NASA-Near-Earth-Object-Analysis.git
   cd NASA-Near-Earth-Object-Analysis
   ```

2. Install dependencies:
   ```bash
   pip install -r requirements.txt
   ```

3. Launch the Jupyter Notebook:
   ```bash
   jupyter notebook
   ```

4. Open `NASA_Near_Earth_Object_Analysis.ipynb` to explore the analysis.

## Usage

1. **Data Loading**: Load and preprocess the dataset.
2. **EDA**: Visualize and interpret data distributions.
3. **Clustering**: Group NEOs and analyze profiles.
4. **Modeling**: Train and evaluate machine learning models for classification.
5. **Interactive Visualizations**: Generate dynamic plots with Plotly.

## Key Visualizations

- **Time Series Analysis**: Observe trends in close approaches over time.
- **Cluster Visualizations**: 3D scatter plots to explore relationships between clusters.
- **Risk Profiles**: Bar charts and tables summarizing cluster characteristics.

## Future Enhancements

- Incorporate live NASA API data for real-time analysis.
- Enhance risk profiling with additional data features.
- Experiment with deep learning models for predictive tasks.

