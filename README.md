# Market Data Dashboard

A real-time market data dashboard showing global market indices with historical performance charts. The dashboard includes data from US, European, and Indian markets.

## Features

- Real-time market data updates
- Historical performance charts (30-day view)
- Support for multiple global markets:
  - US Markets (S&P 500, Dow Jones, NASDAQ, Russell 2000)
  - European Markets (FTSE 100, DAX)
  - Indian Markets (NIFTY 50, SENSEX)
- Auto-refresh functionality
- Interactive charts with tooltips
- Responsive design

## Setup

1. Clone the repository:
```bash
git clone https://github.com/joshmo01/market-data.git
cd market-data
```

2. Install dependencies:
```bash
npm install
```

3. Create a `.env` file in the root directory and add your Alpha Vantage API key:
```
REACT_APP_ALPHA_VANTAGE_KEY=your_api_key_here
```

4. Start the development server:
```bash
npm start
```

## Technologies Used

- React
- Recharts for data visualization
- Tailwind CSS for styling
- Alpha Vantage API for market data

## Configuration

The dashboard is configured to fetch data every 5 minutes. You can modify the refresh interval in the `WorkingMarketData` component.

## API Usage

This project uses the Alpha Vantage API for market data. Please note the following rate limits:
- 5 API calls per minute
- 500 API calls per day (free tier)

## Contributing

Feel free to submit issues and pull requests.

## License

MIT License