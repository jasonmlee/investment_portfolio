# Portfolio Construction Project with Riskfolio

## Overview
This project showcases portfolio construction skills using the **Riskfolio-Lib** library. The objective is to create an optimal portfolio that balances risk and return based on modern portfolio theory and other advanced optimization techniques.

The project is structured to demonstrate the complete process of:

1. **Problem Definition**: Setting investment goals and constraints.
2. **Data Collection**: Gathering historical financial data for analysis.
3. **Portfolio Construction**: Using Riskfolio-Lib to create efficient portfolios.
4. **Visualization**: Displaying results through efficient frontiers and allocation breakdowns.
5. **Performance Analysis**: Backtesting the portfolio and comparing it to benchmarks.

## Features
- **Portfolio Optimization**: Constructs portfolios based on Mean-Variance, Black-Litterman, and other methods.
- **Risk Analysis**: Visualizes the risk contributions of different assets.
- **Efficient Frontier Visualization**: Shows optimal portfolios for different risk levels.
- **Backtesting**: Evaluates portfolio performance against benchmarks.

## Installation

1. Clone the repository:
   ```bash
   git clone https://github.com/yourusername/portfolio-construction-riskfolio.git
   cd portfolio-construction-riskfolio
   ```

2. Create the Conda Environment using the environment.yml file
   ```bash
   conda env create -f environment.yml
   ```

3. Activate the Environment
   ```bash
   conda activate 
   ```

## Usage

1. Download historical price data for assets using your preferred method (e.g., Yahoo Finance).
2. Place the data in the `data/` folder as a CSV file.
3. Run the main script to construct and analyze the portfolio:
   ```bash
   python main.py
   ```
4. View results and visualizations in the `output/` folder.

## Project Structure

```
portfolio-construction-riskfolio/
├── data/             # Folder for input data (CSV files)
├── notebooks/        # Jupyter notebooks for interactive exploration
├── scripts/          # Python scripts for portfolio optimization and analysis
├── output/           # Generated plots and reports
├── requirements.txt  # List of dependencies
├── README.md         # Project documentation
└── main.py           # Main script to run the project
```

## Dependencies
- Python 3.11
- pandas 2.2.2
- numpy 2.2.1
- matplotlib 3.9.2
- Riskfolio-Lib 6.3
- scikit-learn 1.5.2
- yfinance 0.2.51

See [environment.yml](https://github.com/jasonmlee/portfolio-construction-riskfolio/blob/main/environment.yml) for full list of dependencies.

## Example Results

### Efficient Frontier
![Efficient Frontier](images/efficient_frontier_example.png)

### Allocation Breakdown
![Allocation Breakdown](images/allocation_breakdown_example.png)

## Contribution
Contributions are welcome! Feel free to fork the repository and submit pull requests. If you encounter any issues, please open a ticket on the Issues tab.

## License
This project is licensed under the MIT License. See the LICENSE file for details.

## Acknowledgments
- [Riskfolio-Lib Documentation](https://riskfolio-lib.readthedocs.io/en/latest/)
- [Yahoo Finance](https://finance.yahoo.com/) for historical data.
- Inspiration from Modern Portfolio Theory by Harry Markowitz.

---

Happy investing! 🎯
