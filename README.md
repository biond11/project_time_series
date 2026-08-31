# Microsoft and Exxon Mobil Corporations: Time series forecasting 
The prediction task is to estimate the daily adjusted closing price of Microsoft Corp. (MSFT) and Exxon Mobil Corp. (XOM) for the next business day (t+1) using the information available up to the current business day (t). The dataset includes equity-specific variables and macroeconomic indicators that influence the US equity market. 

# Data Dictionary

| Variable Name | Description | Market Segment | Unit |
| :--- | :--- | :--- | :--- |
| `adjprice` | Daily adjusted closing price (Target) | US Equity | USD |
| `volume` | Daily number of shares traded | US Equity | Shares |
| `sp500` | Value of the S&P 500 Market Index | Market Index | USD |
| `vix` | CBOE Volatility Index ("Fear Index") | Market Index | Index Points |
| `oil` | WTI Crude Oil futures price | Commodity | USD / barrel |
| `gold` | Gold futures price | Commodity | USD / ounce |
| `rates_10y` | Yield of the 10-year US Treasury Note | Interest Rate | % |

### Dataset Specifications

- **Temporal Coverage:** 04/01/2010 – 31/12/2025
- **Temporal Resolution:** Daily (Business Days only)
- **Missing Values:** Encoded as `-999`
