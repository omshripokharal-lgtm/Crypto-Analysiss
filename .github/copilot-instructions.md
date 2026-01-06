# Crypto Analysis Project - AI Agent Instructions

## Project Overview
This is a cryptocurrency market analysis project that fetches data from CoinGecko API, processes it, and visualizes insights using Power BI dashboards. The project focuses on market metrics like price changes, market cap, and momentum scoring.

## Architecture
- **Data Flow**: Raw API data → Cleaned datasets → Power BI reports/dashboards
- **Key Components**:
  - `raw_data/`: Contains raw CoinGecko API responses and endpoint documentation
  - `clean_data/`: Processed datasets ready for analysis
  - Power BI files: Dashboards with DAX formulas for calculations

## Critical Workflows
- **Data Fetching**: Use CoinGecko API endpoint: `https://api.coingecko.com/api/v3/coins/markets?vs_currency=usd&order=market_cap_desc&per_page=100&page=1&price_change_percentage=24h,7d`
- **Data Processing**: Transform raw API data into structured clean_data format
- **Visualization**: Build Power BI dashboards with momentum calculations, price change analysis, and market cap rankings

## Project Conventions
- Store raw API data in `raw_data/` directory
- Place processed/cleaned datasets in `clean_data/` directory
- Document API endpoints and measures in markdown files (e.g., `api.md`, `desc.md`)
- Use Power BI for all visualizations and DAX for calculations

## Key Files
- [README.md](README.md): Project overview and installation instructions
- [raw_data/api.md](raw_data/api.md): API documentation and example endpoints
- [clean_data/desc.md](clean_data/desc.md): Data processing descriptions and DAX measures

## Integration Points
- **CoinGecko API**: Primary data source for crypto market data
- **Power BI**: Required for data visualization and analysis features
- No external dependencies beyond Power BI installation

## Development Patterns
- When adding new analysis features, first fetch relevant data via CoinGecko API
- Process data into clean format before importing to Power BI
- Use DAX for calculated columns like momentum scores and price change percentages
- Document new measures and formulas in `desc.md` files