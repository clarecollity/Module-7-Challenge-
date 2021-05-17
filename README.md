# Module-7-Challenge- Creating a Web Application for an ETF Analyzer

# Overview

This project is used to help with passive investing, which helps reduce risk by investing in a basket of assets instead of a single stock. This diversification is done by investing in an exchange-traded fund, or ETF. 

---

# How to Use

To use this analysis of a hypothetical ETF, we calculate the daily returns of the stocks in the ETF individually and together. We do this by reading in info for one of the stocks from the database into a Pandas dataframe in Jupyter Lab. We then use hvplot to create an interactive graph of the daily returns and the annualized return data. 

---

<img width="1440" alt="Screen Shot 2021-05-16 at 10 19 45 PM" src="https://user-images.githubusercontent.com/81061058/118436062-f2cf0280-b694-11eb-9fdc-9e251e3161ce.png">

as shown above, we use the cumprod() function to find the cumulative returns of the ETF portfolio 
