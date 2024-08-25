# Limitless FinPro: Customer Segmentation and CLV Analysis

This repository contains the code and analysis for the **Limitless FinPro: Customer Segmentation and CLV (Customer Lifetime Value) Analysis** project. The aim of this project is to analyze customer data, segment customers into distinct groups based on their characteristics, and provide actionable business insights to enhance marketing strategies and increase customer lifetime value.

## Table of Contents

- [Project Overview](#project-overview)
- [Data Description](#data-description)
- [Project Structure](#project-structure)
- [Installation](#installation)
- [Usage](#usage)
- [Results](#results)
- [Business Recommendations](#business-recommendations)
- [Contributing](#contributing)
- [License](#license)

## Project Overview

In the competitive landscape of financial services, understanding customer segments and predicting customer lifetime value (CLV) is crucial. This project utilizes clustering techniques and predictive modeling to segment customers, analyze their characteristics, and derive insights that drive targeted marketing strategies. By focusing on customer segments with higher CLV, the business can optimize its resource allocation, increase customer satisfaction, and improve overall profitability.

## Data Description

The dataset used in this project includes various features related to customer demographics, insurance policies, and claims. Key features include:

- **Customer Lifetime Value (CLV)**: The projected revenue a customer will generate over their lifetime.
- **Income**: Customer's annual income.
- **Monthly Premium Auto**: The amount a customer pays monthly for auto insurance.
- **Coverage Type**: The type of insurance coverage (Basic, Extended, Premium).
- **Employment Status**: Employment status of the customer (Employed, Unemployed, etc.).
- **Vehicle Class**: The class of the customer's vehicle (SUV, Sedan, etc.).
- **Policy Level**: The level of the insurance policy (L1, L2, L3).
- **Sales Channel**: The channel through which the customer purchased their insurance (Agent, Branch, Web, etc.).

## Project Structure

The repository is structured as follows:

```
Limitless-FinPro/
│
├── data/
│   ├── raw/                 # Raw data files
│   ├── processed/           # Processed data files
│
├── notebooks/
│   ├── Limitless_Finpro.ipynb  # Jupyter Notebook containing the main analysis
│
├── src/
│   ├── data_processing.py    # Scripts for data cleaning and processing
│   ├── clustering_analysis.py # Scripts for clustering analysis
│   ├── modeling.py           # Scripts for predictive modeling
│   ├── visualization.py      # Scripts for generating plots and visualizations
│
├── README.md                 # Project description and instructions
├── requirements.txt          # List of dependencies
└── LICENSE                   # License for the repository
```

## Installation

To set up the project locally, follow these steps:

1. **Clone the repository**:
   ```bash
   git clone https://github.com/yourusername/Limitless-FinPro.git
   cd Limitless-FinPro
   ```

2. **Create a virtual environment and activate it**:
   ```bash
   python -m venv venv
   source venv/bin/activate   # On Windows use `venv\Scripts\activate`
   ```

3. **Install the required dependencies**:
   ```bash
   pip install -r requirements.txt
   ```

## Usage

To run the analysis, open the Jupyter Notebook located in the `notebooks` directory:

```bash
jupyter notebook notebooks/Limitless_Finpro.ipynb
```

The notebook contains step-by-step instructions for data processing, clustering, predictive modeling, and visualization. Follow the instructions in the notebook to replicate the analysis and view the results.

## Results

The results of the analysis reveal distinct customer segments, each with unique characteristics and behaviors. Key findings include:

- **Cluster 0**: Highly engaged customers who prefer basic and premium coverage.
- **Cluster 1**: Moderately engaged customers, often opting for mid-tier insurance products.
- **Cluster 2**: High-value customers with a preference for comprehensive coverage and higher premiums.
- **Cluster 3**: Cost-conscious customers who prefer basic coverage and exhibit lower overall financial engagement.

## Business Recommendations

Based on the analysis, the following recommendations are made for the marketing team:

1. **Retention Strategies**: Focus on retaining Cluster 0 customers by offering personalized renewal packages and loyalty rewards.
2. **Upsell and Cross-sell**: Target Cluster 2 customers with upsell opportunities, promoting comprehensive coverage options.
3. **Optimize Sales Channels**: Strengthen engagement through preferred channels such as agents and branches, while enhancing digital interactions for tech-savvy customers.

For a detailed analysis and additional recommendations, refer to the notebook and the results section.

## Contributing

If you would like to contribute to this project, please fork the repository and submit a pull request. All contributions are welcome!

## License

This project is licensed under the MIT License - see the [LICENSE](LICENSE) file for details.
