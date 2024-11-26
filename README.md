# Aqua-Biomass
Data science methodology and modeling with Fish-Stocks dataset

# Fish Stocks & Overfishing Impact Analysis

## Project Summary

This project aims to analyze the impact of fishing activity reductions on aquatic life, specifically focusing on fish stocks and diversity across different continents. The primary goal is to examine how repeated fishing in the same areas affects the recovery of aquatic populations and the surrounding environment. Through data analysis and forecasting, this project highlights the consequences of overfishing on the global food chain and the effectiveness of various fisheries management measures.

### Main Question:
- **How have reductions in fishing activity on different continents affected fish stocks and diversity?**

### Sub Question:
- **How does repeated fishing in the same area affect the recovery of the aquatic population and the environment?**

### Objectives:
1. **Analyze the trend of the decline of aquatic animal populations worldwide.**
2. **Investigate the relationship between overfishing and its impact on the food chain in the ecosystem.**
3. **Evaluate the effectiveness of fisheries management measures.**

### Approach:
To answer these questions, we utilize the **Fish_stocks** dataset and apply **XGBoost** for forecasting the future state of fish stocks. This approach enables us to predict how fish populations may evolve based on current fishing practices and management efforts. The project also investigates the correlation between overfishing and its disruptive impact on aquatic ecosystems.

### Conclusion:
Based on the findings from the Fish_stocks dataset and the results of the XGBoost model, the study reveals that overfishing significantly disrupts ecological balance. For future sustainability, strict policy enforcement combined with public education is essential to ensure the long-term health of aquatic resources and food security.

## Installation Instructions

To run the project on your local machine, follow these steps:

### Prerequisites:
- Python 3.7 or above
- Required Python libraries: `numpy`, `pandas`, `matplotlib`, `xgboost`, `scikit-learn`, `seaborn`

### Steps to run the project:

1. **Clone the repository:**
   ```bash
   git clone https://github.com/your-username/fish-stocks-analysis.git
   cd fish-stocks-analysis

2. **Create virtual environment(optional)**
   ```bash
   pip install venv
   python -m venv .venv
   .venv\Scripts\activate

3. **Install necessary libraries:**
   ```bash
   pip install -r requirements.txt
