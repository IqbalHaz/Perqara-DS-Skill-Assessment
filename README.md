# Perqara Data Science Skill Assessment
By: Alif Iqbal Hazairin <br><br>

This repository contains the analysis and machine learning modeling for a data science skill assessment at Perqara. The project focuses on customer segmentation for an e-commerce transaction dataset, seemingly from a Brazilian online shop, using RFM (Recency, Frequency, Monetary) analysis.

## Repository Structure

- **`datasets/`**: Folder containing the datasets used in the analysis.
- **`basic_exploration/`**: Jupyter Notebook files for basic data exploration on each dataset.
- **`rfm_analysis.ipynb`**: Jupyter Notebook file containing the full analysis, including:
  - RFM Analysis to segment customers.
  - Predictive modeling to classify customers into segments based on individual RFM scores (NB: not the cluster itself).
- **`model.pkl`**: The saved ML predictive model.

## Getting Started

1. **Clone the repository:**
   ```bash
   git clone https://github.com/IqbalHaz/Perqara-DS-Skill-Assessment.git
   cd Perqara-DS-Skill-Assessment
   ```

2. **Install required dependencies:**
   ```bash
   pip install -r requirements.txt
   ```

3. **Open the Jupyter Notebook:**
   ```bash
   jupyter notebook rfm_analysis.ipynb
   ```

## Analysis Overview

- **RFM Analysis:** Segments customers based on their recency, frequency, and monetary value of purchases.
- **Predictive Modeling:** Trains a machine learning model to classify customers into the identified segments based on RFM scores.

## Usage

- Explore the `datasets/` folder for raw data.
- Review the data exploration notebooks in `basic_exploration/` for initial insights.
- Follow the detailed analysis and modeling in `rfm_analysis.ipynb` for the complete process.

## License

This project is licensed under the MIT License.