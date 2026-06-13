# MSFT Financial Data Automation Pipeline

Automated Python pipeline to pull, clean and validate Microsoft quarterly 
financials from SEC filings via Alpha Vantage API.

## What this does
- Pulls 12 quarters of Microsoft income statement data from SEC filings
- Cleans and structures data automatically
- Calculates gross margin, operating margin, net margin, R&D ratio and QoQ growth
- Validates output against Microsoft's officially reported figures
- Exports clean Excel file ready for analysis

## How to use
1. Get a free API key at alphavantage.co/support/#api-key
2. Replace "API_KEY" in the notebook with your key
3. Run all cells in order

## Built by
Shruti Gupta | MS Finance, Fordham University
