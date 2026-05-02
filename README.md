# Equity Portfolio Analysis Model

Excel-based financial model for tracking portfolio performance, allocation, and daily P&L.

## Inputs
- Stock tickers (Excel Data Types)
- Prices (auto-updated)
- Quantity held
- Management fee: 3%
- Trading days: 252

## Calculations
- Market Value = Price × Quantity
- Total AUM = Sum of market values
- Weight (%) = Position / Total AUM
- Portfolio Return = SUMPRODUCT(Weights, Returns)
- Daily P&L = AUM × Portfolio Return
- Management Fee (Daily) = AUM × Fee / Trading Days

## Dashboard Features
- Portfolio Allocation (Pie Chart)
- Top Holdings by Weight (Bar Chart)
- Key metrics: AUM, Return, Daily P&L

## Preview
![Dashboard](Portfolio_Dashboard_Overview.png)

## Author
Venessa Dsouza
