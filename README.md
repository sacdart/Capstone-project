# Capstone Project: Global Emissions Data Analytics and Clustering

A comprehensive data analytics capstone project that analyzes global environmental and emissions data using machine learning clustering techniques and time series forecasting. This project examines the relationships between population, GDP, and various types of emissions (CO₂, methane, nitrous oxide, and total GHG) across different countries and regions.

## 📊 Project Overview

This project performs advanced data analysis on global emissions data to:
- Identify patterns and relationships between economic indicators and environmental emissions
- Cluster countries based on their emission profiles using K-Means clustering
- Forecast future emission trends using ARIMA time series models
- Visualize correlations and patterns through comprehensive data visualizations

## 🛠️ Technologies Used

- **Python 3.13**
- **Data Processing & Analysis:**
  - Pandas - Data manipulation and analysis
  - NumPy - Numerical computations
- **Machine Learning:**
  - scikit-learn - K-Means clustering, StandardScaler, t-SNE dimensionality reduction
  - statsmodels - ARIMA time series forecasting
- **Data Visualization:**
  - Matplotlib - Creating plots and charts
  - Seaborn - Statistical data visualization
- **Development Environment:**
  - Jupyter Notebook - Interactive data analysis and visualization

## 📁 Project Structure

```
Capstone-project/
├── code/
│   ├── code.ipynb          # Main Jupyter notebook with analysis
│   └── code.html           # HTML export of the notebook
├── graph/
│   ├── arima_forecasts_6_types.png          # ARIMA forecasts visualization
│   ├── emission_forecasts_ppt_ready.png     # Presentation-ready forecasts
│   ├── slide8_correlation_focused.png       # Correlation heatmap
│   ├── slide9_pairplot_minimal.png          # Pairplot of variables
│   └── output*.png                          # Additional analysis outputs
├── Data set presentation.pdf   # Dataset presentation (8 pages)
├── LICENSE                     # Project license
└── README.md                   # This file
```

## 🚀 Getting Started

### Prerequisites

- Python 3.13 or higher
- Jupyter Notebook or JupyterLab

### Installation

1. Clone the repository:
```bash
git clone https://github.com/sacdart/Capstone-project.git
cd Capstone-project
```

2. Install required dependencies:
```bash
pip install pandas numpy scikit-learn statsmodels matplotlib seaborn jupyter
```

### Usage

1. Navigate to the code directory:
```bash
cd code
```

2. Launch Jupyter Notebook:
```bash
jupyter notebook code.ipynb
```

3. Run the cells sequentially to reproduce the analysis

## 🔍 Analysis Features

### 1. Exploratory Data Analysis (EDA)
- Comprehensive data preprocessing and cleaning
- Statistical summary of key variables
- Missing data analysis and handling

### 2. Correlation Analysis
- Examination of relationships between:
  - Population and emissions
  - GDP and emissions
  - Different emission types (CO₂, methane, nitrous oxide, total GHG)
- Visualization through correlation heatmaps and pairplots

### 3. K-Means Clustering
- Clustering of countries based on emission profiles
- Elbow method optimization (optimal k=4-5 clusters)
- t-SNE dimensionality reduction for 2D visualization
- Cluster pattern identification and interpretation

### 4. Time Series Forecasting
- ARIMA models applied to 6 different emission types
- Future emission trend predictions
- Model validation and performance evaluation

## 📈 Visualizations

The project includes several key visualizations in the `/graph` folder:

1. **ARIMA Forecasts** - Multi-panel forecasts for 6 emission types
2. **Emission Forecasts** - Presentation-ready forecast visualizations
3. **Correlation Heatmap** - Visual representation of variable relationships
4. **Pairplot** - Scatter plot matrix showing population, GDP, and emissions relationships
5. **Additional Outputs** - Various clustering and trend analysis visualizations

## 📄 Dataset

The dataset includes global environmental and economic indicators:
- Population data by country
- GDP figures
- CO₂ emissions
- Methane emissions
- Nitrous oxide emissions
- Total greenhouse gas (GHG) emissions

For detailed information about the dataset, refer to `Data set presentation.pdf`.

## 📊 Key Findings

The analysis reveals important patterns in global emissions data through:
- Clustering that groups countries with similar emission profiles
- Strong correlations between economic indicators and environmental impact
- Predictive models for understanding future emission trends
- Visual insights suitable for academic and professional presentations

## 📝 License

This project is licensed under the terms specified in the LICENSE file.

## 🤝 Contributing

This is a capstone project. For questions or suggestions, please open an issue in the repository.

## 📧 Contact

For more information about this project, please refer to the repository or contact the project maintainer.

---

**Note:** This project was developed as part of a data analytics capstone demonstrating proficiency in Python, machine learning, statistical analysis, and data visualization.
