# Analysis of connection between bitcoin and google trends time series in R

The notebook studies the relation between bitcoin and google trends time series by:
<li> Pearson correlation
<li> Granger causality test
<li> Impulse Response Function
<li> Variance decomposition of forecast errors 

Data includes weekly log-returns of: bitcoin and popularity of search term 'bitcoin" derived from Google Trends
Weekly log returns of google trends popularity means the log(r(t)/r(t-1)), where r is the popularity of search term 'bitcoin'

Price of bitcoin was derived from quandl: https://www.quandl.com/data/BCHAIN/MKPRU-Bitcoin-Market-Price-USD
Popularity of search term 'bitcoin" was derived from Google Trends: https://trends.google.com/trends/explore?q=bitcoin&geo=US
