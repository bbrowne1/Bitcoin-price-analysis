![image](https://github.com/user-attachments/assets/d9e806cb-fe44-4591-8a1e-b577e95249cf)
# Bitcoin Price Analysis

This repository contains a Jupyter Notebook (`bitcoin-price-analysis.ipynb`) that explores Bitcoin price data from 2017 to 2023. The analysis focuses on understanding Bitcoin's price trends, trading volume, and other key metrics over time. The dataset used in this analysis is sourced from [Kaggle](https://www.kaggle.com/datasets/jkraak/bitcoin-price-dataset).

## Table of Contents
1. [Introduction](#introduction)
2. [Dataset](#dataset)
3. [Analysis Outline](#analysis-outline)
4. [Key Findings](#key-findings)
5. [Usage](#usage)
6. [Dependencies](#dependencies)
7. [License](#license)

## Introduction
Bitcoin has emerged as a dominant force in the cryptocurrency market, often referred to as "digital gold." This analysis delves into Bitcoin's price data to understand its behavior as a store of value. The notebook explores various aspects of Bitcoin's price, including open, high, low, and close prices, trading volume, and the number of trades over time.

## Dataset
The dataset used in this analysis contains Bitcoin price data from August 17, 2017, to August 1, 2023. It includes the following columns:

- **timestamp**: The date and time of the data point.
- **open**: The opening price of Bitcoin at the start of the time interval.
- **high**: The highest price of Bitcoin during the time interval.
- **low**: The lowest price of Bitcoin during the time interval.
- **close**: The closing price of Bitcoin at the end of the time interval.
- **volume**: The trading volume of Bitcoin during the time interval.
- **quote_asset_volume**: The volume of the quote asset (e.g., USD) traded.
- **number_of_trades**: The number of trades executed during the time interval.
- **taker_buy_base_asset_volume**: The volume of the base asset (Bitcoin) bought by takers.
- **taker_buy_quote_asset_volume**: The volume of the quote asset bought by takers.

## Analysis Outline
The analysis is structured as follows:

1. **Data Preparation and Cleaning**:
   - Load the dataset.
   - Check for missing values and clean the data.
   - Convert the `timestamp` column to a datetime format.

2. **Exploratory Analysis and Visualization**:
   - Analyze the price trends over time.
   - Explore trading volume and the number of trades.
   - Break down the data by year to observe yearly trends.

3. **Questions and Answers**:
   - What is the date range of the dataset?
   - How many unique trades occurred during the period?
   - What are the key statistics for Bitcoin's price and volume?

4. **Summary and Conclusion**:
   - Summarize the key findings.
   - Provide insights into Bitcoin's price behavior over time.

## Key Findings
- The dataset covers Bitcoin price data from **August 17, 2017**, to **August 1, 2023**.
- There are **18,985 unique trades** recorded in the dataset.
- The analysis reveals trends in Bitcoin's price and trading volume, with significant fluctuations observed over the years.

## Usage
To run the analysis, follow these steps:

1. **Clone the repository**:
   ```bash
   git clone https://github.com/your-username/bitcoin-price-analysis.git
   cd bitcoin-price-analysis
   ```

2. **Install dependencies**:
   Ensure you have the required Python libraries installed. You can install them using `pip`:
   ```bash
   pip install pandas numpy matplotlib seaborn opendatasets
   ```

3. **Run the Jupyter Notebook**:
   Open the notebook in Jupyter:
   ```bash
   jupyter notebook bitcoin-price-analysis.ipynb
   ```

4. **Follow the notebook**:
   Execute the cells in the notebook to perform the analysis and visualize the results.

## Dependencies
The following Python libraries are required to run the analysis:

- **pandas**: For data manipulation and analysis.
- **numpy**: For numerical computations.
- **matplotlib**: For data visualization.
- **seaborn**: For enhanced data visualization.
- **opendatasets**: For downloading the dataset from Kaggle.

## License
This project is licensed under the MIT License. See the [LICENSE](LICENSE) file for details.

---

For any questions or feedback, feel free to open an issue or contact the repository owner.
![Visitor Count](https://komarev.com/ghpvc/?username=bbrowne1&color=blue)

