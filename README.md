# LEGO Resale Model

This repository contains analysis and modeling of LEGO set resale values, including data processing, visualization, and predictive modeling.

## Repository Structure

- `p8_lego_Code.ipynb`: Main Jupyter notebook containing the analysis and modeling code
- `datafiles/`: Directory containing the required datasets
  - `sets.csv`: Dataset containing LEGO set information
  - `reduced_lego_data.csv`: Processed dataset for analysis
- `p8-lego Final Paper.pdf`: Final research paper documenting the analysis and findings

## Prerequisites

To reproduce the results, you'll need:

- Python 3.x
- Jupyter Notebook
- Required Python packages (install using pip):
  ```
  pandas
  numpy
  matplotlib
  seaborn
  scikit-learn
  ```

## Setup Instructions

1. Clone this repository:

   ```bash
   git clone https://github.com/mhines2/lego-resale-model.git
   cd lego-resale-model
   ```

2. Install required Python packages:

   ```bash
   pip install -r requirements.txt
   ```

3. Ensure the data files are in the correct location:
   - The `sets.csv` and `reduced_lego_data.csv` files should be in the `datafiles/` directory

## Reproducing the Results

1. Open the Jupyter notebook:

   ```bash
   jupyter notebook p8_lego_Code.ipynb
   ```

2. Run all cells in the notebook sequentially to reproduce the analysis and visualizations

3. The notebook contains:
   - Data loading and preprocessing
   - Exploratory data analysis
   - Feature engineering
   - Model development and evaluation
   - Results visualization

## Data Sources

The analysis uses two main datasets:

- `sets.csv`: Contains information about LEGO sets including set numbers, names, themes, and release years
- `reduced_lego_data.csv`: Processed dataset containing additional features and target variables for the analysis

## Results

The final results and findings are documented in the `p8-lego Final Paper.pdf`. The paper includes:

- Detailed analysis of LEGO set resale values
- Key factors affecting resale prices
- Predictive models for estimating resale value
- Visualizations and insights
