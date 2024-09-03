# Financial Market Web Scraping Project
## The Impact of Central Bank Policy Rate on Bond and Stock Investors

### Overview
In today’s economic climate, understanding the dynamic interplay between the **central bank’s policy rates**, **short-term benchmark bond yields**, and **stock market index** is essential to grasp how investors operate within financial markets and the impact on the broader economy. This project aims to examine these relationships to provide insights into financial market behavior and economic implications.

### Objectives
- **Examine Policy Rate Effectiveness**: Analyze the impact and effectiveness of central bank policy rates.
- **Assess Time Series Relationships**: Evaluate the relationships between policy rates, bond yields, and stock market index data.
- **Understand Investor Implications**: Explore how these relationships influence investor behavior and the broader economy.

### Data Sources
We gather data through web scraping using Selenium to capture the following time series:
- **Stock Market Index Data**: Daily index data from the [Toronto Stock Exchange (TSX)](https://money.tmx.com/en). This data provides insights into stock market performance.
- **Bank of Canada Policy Rates**: [Daily policy rates](https://www.bankofcanada.ca/core-functions/monetary-policy/key-interest-rate/) from the Bank of Canada's website. This data provides insights into the performance of the economy over economic cycles.
- **2-Year Benchmark Bond Yields**: [Short-term bond yields](https://www.bankofcanada.ca/rates/interest-rates/canadian-bonds/) from the Bank of Canada's website. This information is crucial for understanding the impact of monetary policy on the yield curve.

### Methodology
- **Web Scraping**: Data is collected using Selenium to automate the extraction of relevant information from the specified webpages.
- **Data Analysis**: We analyze the collected data to assess the relationships between policy rates, bond yields, and stock market performance.

### Findings
- **Policy Rate Impact**: The financial market series tend to follow the target policy rate. As rates rise, investors adjust their decisions between stocks and bonds.
- **Correlation Analysis**: The correlation coefficient between the yield curve and the target policy rate was found to be 93%, indicating a strong relationship. In contrast, the correlation between the target policy rate and stock performance was 43%, suggesting a weaker connection. This indicates that bond investors are more sensitive to changes in the policy rate compared to stock investors.
- **Economic Recession****: During economic downturns, investors prefer Central Bank Open Market Operations (OMO) instruments, leading to a simultaneous negative movement in both the short-term yield curve and the stock index.

### Tools and Technologies
- **Selenium**: For web scraping and data extraction from webpages.
- **Python**: For data processing and analysis.
- **Pandas**: For data manipulation and analysis.
- **Plotly**: For data visualization.

### Conclusion
This project provides valuable insights into how policy rates, bond yields, and stock market performance interact. By analyzing these relationships, we can better understand investor behavior and its impact on the broader economy.

<img width="649" alt="image" src="https://github.com/user-attachments/assets/883d3914-daa8-43d8-80ad-56343f096d3c">


