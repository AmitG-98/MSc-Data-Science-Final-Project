
# Global Macroeconomic Dashboard with Predictive Analytics

This repository contains the code and related documentation for the MSc Data Science Final Project, titled **"Global Macroeconomic Dashboard with Predictive Analytics"**. The project was developed by **Amit Subhash Gurav (SRN: 22024186)** under the supervision of **John Evans** at the University of Hertfordshire.

## Project Overview

The **Global Macroeconomic Dashboard** is an interactive platform designed to monitor and forecast key macroeconomic indicators, including:

- GDP Growth
- Inflation
- Unemployment
- Real Interest Rates

The dashboard uses **predictive analytics** with models such as ARIMA, XARIMA, and LSTM, providing short- and medium-term economic forecasts based on historical and real-time data.

### Key Features
- **Predictive Modeling**: Forecasts economic trends for the next five years using time-series analysis.
- **Interactive Visualization**: User-friendly interface with visual tools for exploring macroeconomic trends.
- **Real-Time Data Pipelines**: Incorporates data from reliable sources like the World Bank and IMF.
- **Global Risk Index**: Assesses economic stability across regions.
- **Scenario Analysis**: Allows users to simulate potential economic outcomes.

### Target Users
- Economists
- Policymakers
- Investment Firms
- Multinational Corporations

---

## Project Files

- **`Final_Structured_Code.ipynb`**: The main Jupyter Notebook containing the code for data preprocessing, modeling, and visualization.
- **Data Folder**: Contains the cleaned datasets used for analysis (referenced in the code).

---

## How to Use

### Prerequisites

1. **Python 3.8 or later**: Install from [python.org](https://www.python.org/).
2. **Libraries**:
   - Install required packages by running:
     ```bash
     pip install -r requirements.txt
     ```
3. **Jupyter Notebook**: Ensure Jupyter Notebook or JupyterLab is installed to run `.ipynb` files.

### Running the Project

1. Clone this repository:
   ```bash
   git clone https://github.com/AmitG-98/MSc-Data-Science-Final-Project.git
   ```
2. Navigate to the project folder:
   ```bash
   cd MSc-Data-Science-Final-Project
   ```
3. Open the Jupyter Notebook:
   ```bash
   jupyter notebook Final_Structured_Code.ipynb
   ```
4. Follow the instructions in the notebook to preprocess data, train models, and visualize results.

---

## Results

The project demonstrated that:
- **ARIMA** is the most reliable model for short-term and seasonal forecasting.
- **XARIMA** is more realastic
- GDP trends in developed countries are more stable, while developing countries experience higher volatility.
- Future enhancements could include hybrid models, more economic indicators, and sector-specific dashboards.

---

## Future Work

1. Expand datasets to include least-developed countries and additional indicators (e.g., trade balances, government spending).
2. Experiment with advanced machine learning models (e.g., GRU, attention-based LSTM).
3. Implement real-time forecasting and policy simulations.

---

## Citation

If you use this code or insights from the project, please cite as follows:
```
Gurav, A. S. (2024). Global Macroeconomic Dashboard with Predictive Analytics. MSc Data Science Final Project, University of Hertfordshire.
```

---
## Acknowledgments

Special thanks to:
- **Supervisor**: John Evans for invaluable guidance.
- **World Bank & IMF** for providing open-access datasets.
- Friends and family for their support throughout the project.

---

## Contact

For questions or feedback, feel free to reach out via [GitHub Issues](https://github.com/AmitG-98/MSc-Data-Science-Final-Project/issues).
