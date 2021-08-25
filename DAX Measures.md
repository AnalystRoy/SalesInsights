# Measures created using DAX

Total Profit Margin = `Total Profit Margin = SUM('Transactionss'[Profit_Margin])`

Profit Margin % -  `Profit Margin % = DIVIDE([Total Profit Margin],[Revenue],0)`

Profit Margin Contribution % -  `Profit Margin Contribution % = DIVIDE([Total Profit Margin],CALCULATE([Total Profit Margin],ALL('products'),ALL('customers'),ALL('markets')))`

Revenue Last Year - `Rev LY = CALCULATE([Revenue],SAMEPERIODLASTYEAR('date'[date]))`

Total Revenue- `Revenue = SUM('Transactionss'[conv_amt])`

Revenue Contribution(%)- `Revenue Contribution(%) = DIVIDE([Revenue],CALCULATE([Revenue],ALL('products'),ALL('customers'),ALL('markets')))`


