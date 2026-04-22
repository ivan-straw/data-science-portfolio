A personal data analysis project designed to track, analyse, and forecast the performance of my stock portfolio.

The project combines Python-based data analysis, interactive dashboards, and structured portfolio management to monitor investments, compare current prices with historical trends, and estimate potential future performance.

Analysis is conducted in Jupyter Notebook using Python, with forecasting visualisations created in Microsoft Power BI and portfolio data organised through Airtable for accessible tracking of holdings and transactions.

Project Goals:
The aim of this project is to create a data-driven system for managing and analysing a personal investment portfolio.

Key objectives include:

Tracking buy and sell transactions
Monitoring current portfolio value
Comparing current stock prices with historical trends
Analysing portfolio performance and allocation
Creating visual forecasts of potential portfolio value over the next year

DATA PIPELINE STRUCTURE:
The analysis is built around a set of structured dataframes that represent different parts of the portfolio workflow.

Transactions Data
transactions_df

Contains the raw trade history of the portfolio.

  Includes:
    Stock ticker
    Transaction date
    Buy or sell indicator
    Number of shares
    Transaction price

This dataframe acts as the foundation of the portfolio data model.


Current Price Data
prices_df

Stores the latest market prices for each stock in the portfolio.

Data is retrieved using a financial market API, enabling the portfolio value to be updated dynamically.


Portfolio Positions
positions_df

Aggregates the transaction history to determine the current holdings for each stock.

This includes:

Total shares currently held
Average purchase price
Portfolio positions by ticker


Portfolio Performance
portfolio_df

Combines positions with current market prices to calculate:

Total value of each holding
Unrealised gains or losses
Portfolio allocation weights
Overall portfolio value

This dataframe provides a complete snapshot of portfolio performance.


Historical Price Data
price_history_df

Contains historical stock price data used for:

Trend analysis
Performance comparison
Forecast modelling

This dataset supports the visualisations and forecasting analysis used throughout the project.



FORECASTING & VISUALISATION
Using the historical price dataset, line charts are created to visualise potential future trends for each stock in the portfolio.

Forecasting dashboards built in Power BI allow users to:

Compare historical and predicted prices
Explore stock performance over time
Visualise projected financial positions over the next year

These visualisations provide a clear overview of potential portfolio growth and risk exposure.



TOOLS
Python
Pandas
NumPy
Matplotlib / Seaborn

Data & Analytics Tools:

Jupyter Notebook
Microsoft Power BI
Airtable



KEY SKILLS
This project demonstrates practical data analytics and data science skills including:

Data cleaning and preprocessing
Portfolio and financial data analysis
Exploratory data analysis (EDA)
Time series trend analysis
Forecasting visualisation
Dashboard development
Data modelling using structured dataframes
Multi-tool analytics workflows


FUTURE IMPROVEMENTS
Potential extensions for the project include:

  Automated data pipelines for real-time price updates
  Machine learning models for stock price prediction
  Portfolio risk metrics (volatility, Sharpe ratio, drawdown)
  Scenario analysis for portfolio growth
  Interactive portfolio dashboards
