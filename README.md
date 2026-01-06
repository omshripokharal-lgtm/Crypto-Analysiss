# Crypto Analysis

A cryptocurrency market analysis project that fetches data from the CoinGecko API, processes it, and visualizes key insights using Power BI dashboards. The project focuses on market metrics such as price changes, market capitalization, and momentum scoring to evaluate growth in the crypto market.

## Table of Contents
- [Introduction](#introduction)
- [Dataset / Inputs](#dataset--inputs)
- [Tech Stack](#tech-stack)
- [Installation](#installation)
- [Usage](#usage)
- [Analysis Features](#analysis-features)
- [Results / Insights](#results--insights)
- [Project Structure](#project-structure)
- [Contributing](#contributing)
- [License](#license)
- [Contact](#contact)

## Introduction
This project aims to make cryptocurrency data easier to understand and analyze. It provides visual dashboards that highlight market movements, growth patterns, and high-performing cryptocurrencies. Key areas include risk analysis, portfolio valuation, and trend identification to support informed decision-making in the crypto market.

## Dataset / Inputs
- **Raw Data**: Fetched from CoinGecko API (e.g., `https://api.coingecko.com/api/v3/coins/markets?vs_currency=usd&order=market_cap_desc&per_page=100&page=1&price_change_percentage=24h,7d`)
- Includes metrics like price changes (24h, 7d), market cap, and volume.

## Tech Stack
- **Data Source**: CoinGecko API
- **Visualization**: Power BI Desktop
- **Data Processing**: Manual cleaning and transformation (no code-based scripts in current setup)

## Installation
1. Clone the repository:
   ```bash
   git clone https://github.com/your-username/crypto-analysis.git
   ```
2. Ensure Power BI Desktop is installed for data visualization.
3. Check and install any required dependencies mentioned in the project files (none currently specified).

## Usage
1. Open the Power BI files in the repository.
2. Load the cleaned datasets from the `clean_data/` folder.
3. Interact with dashboards to explore metrics like momentum scores, price changes, and market rankings.
4. Use the built-in calculator for portfolio valuation.

## Analysis Features
- Momentum calculation based on growth metrics (growth score, momentum score, rating)
- Price change percentage analysis (24h, 7d)
- Market capitalization ranking and trend analysis
- Comparative performance insights of cryptocurrencies
- Risk analysis (max/min/average values)
- Total amount calculator for portfolio estimation
- Expected 7-day returns and forecasts
- Top 10 24h high/low currencies

## Results / Insights
The project provides clear visual dashboards and analytical insights to understand:
- Market movements and fluctuations
- Growth patterns over time
- High-performing cryptocurrencies
- Overall crypto market trends
- Portfolio value estimation based on selected assets

## Project Structure
```
crypto-analysis/
├── raw_data/          # Raw API data and endpoint documentation
├── clean_data/        # Processed and cleaned datasets
├── Reports/           # Power BI reports, dashboards, DAX formulas, and documentation
├── Results/           # Final analysis outputs and insights
├── README.md          # Project documentation
├── LICENSE            # License file
└── .github/           # GitHub-specific files (e.g., copilot instructions)
```

## Contributing
Contributions are welcome! Please follow these steps:
1. Fork the repository.
2. Create a new branch for your feature.
3. Commit your changes.
4. Push to the branch.
5. Open a Pull Request.

## License
This project is licensed under the terms specified in the [LICENSE](LICENSE) file.

## Contact
For questions or suggestions, please open an issue on GitHub or contact [omshripokharal@gmail.com].