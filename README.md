# Stock-Segmentation-using-Clustering
_
_S&P 500 Stock Clustering & Portfolio Diversification_

**Overview:**
This project analyses the S&P 500 index to cluster stocks based on Daily Return, Beta, and Annual Volatility metrics. The S&P 500 comprises 500 large-cap US companies across various sectors, traded on the NYSE or Nasdaq — making it an ideal dataset for algorithmic clustering and portfolio diversification.
Investing in stocks with different betas helps reduce overall portfolio risk, as varying betas tend to indicate different patterns of return and volatility. By managing exposure across a range of beta values, investors can build more resilient, diversified portfolios.

**Tasks:**
1. Data Loading
Load S&P 500 company and price data from the Wikipedia source linked above.
2. Metric Calculation (Google Colab)
Define and calculate the following metrics for each stock:

Daily Return — percentage change in price day over day
Beta — sensitivity of the stock's return relative to the market
Annual Volatility — standard deviation of daily returns, annualised

3. Metric Illustration
Demonstrate how Daily Return, Beta, and Annual Volatility can be used to segment stocks into categories, helping investors align their portfolios with specific risk tolerances and market strategies.
4. Agglomerative Clustering
Divide the stock portfolio into groups across the three dimensions (Daily Return, Beta, Annual Volatility) using agglomerative (hierarchical) clustering.
5. K-Means Clustering
Divide the stock portfolio into tiered groups across the same three dimensions using K-Means clustering. For each identified cluster, discuss the profile in terms of Beta and Annual Volatility characteristics.
6. CRM & Sustainability in Fintech
Discuss how CRM (Customer Relationship Management) tools contribute to sustainability in Financial Technology (Fintech), highlighting practical benefits and insights into how these systems can support a more sustainable future for businesses.

**Dataset:**

Source: Wikipedia – List of S&P 500 Companies
Scope: 500 large-cap US companies, NYSE & Nasdaq listed
