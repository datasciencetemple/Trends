# Google Trends and Stock Volume 

This project, initiated by the Data Science Department of Temple University, aims to explore the intricate relationship between stock trading volumes and trends in Google search data. Our investigation delves into analyzing patterns and correlations between search interest for specific stock-related terms and the trading volumes of those stocks. Through this research, we aim to uncover insights that could be invaluable for academic researchers and investors.

An interesting data feature discovered by our team highlights a significant link between Google Trends data and stock market activities. This finding has propelled us to conduct preliminary research to further understand the dynamics at play. We are excited to share our initial findings here, with the hope of fostering future research and collaboration.

The preliminary results are updated to this GitHub repository every weekday morning, reflecting our ongoing commitment to transparency and academic sharing. We believe that by making our research accessible, we can encourage a collaborative environment where scholars and practitioners alike can contribute to and benefit from our findings.


## Data Sharing and Compliance Statement:

This research project utilizes publicly available data, including stock market data and Google search trend data. <br>

The stock market data is sourced from Yahoo Finance, which provides open access to financial market information: <br>
https://finance.yahoo.com/ <br>
https://pypi.org/project/yfinance/ <br>

Google Trends data is used under its aggregated form to analyze search interest related to stock market terms. Google Trends: <br> 
https://trends.google.com/trends/ <br> 
https://pypi.org/project/pytrends/ <br>

Both datasets are publicly accessible and do not contain personal or sensitive information. Our use of this data adheres to the terms of service provided by the respective data sources. This project aims to conduct analysis in an ethical manner, respecting the availability and openness of the data used.


## Data Definitions
**ticker**: The stock symbol representing a particular company's shares. <br>

**search_move_24h**: This measures the change in Google Trends search interest for the query composed of the ticker symbol and the word "stock" over the most recent 24 hours, compared to the preceding 24 hours (i.e., the last 48-24 hours period). <br>

**search_move_3d**: This represents the change in Google Trends search interest for the query combining the ticker symbol and "stock" during the latest 24 hours, in comparison to the period covering the 2nd to the 4th day prior. <br>

**search_move_6d**: This indicates the change in Google Trends search interest for the query that includes the ticker symbol and "stock" over the most recent 24 hours, compared to the period spanning the 2nd to the 7th day prior. <br>

**sort**: Entries are sorted based on the search_move_24h value, highlighting the stocks with the most significant changes in search interest over the last 24 hours. <br>

**sector**: The sector to which the ticker belongs, categorizing the company into a specific area of the economy. <br> 


## Invitation for Collaboration
This project is an academic research initiative, and we are open to sharing our findings and collaborating with others in the field. For those interested in delving deeper into our methodology, data sources, and preliminary results, we encourage you to explore the contents of this repository. Your feedback, questions, and suggestions are highly valued as we navigate this fascinating intersection of data science and financial analysis together. If you are interested in contributing to or collaborating on this project, please reach out to us: <br> <br> 
Name: Edo Airoldi <br>
Email: airoldi@temple.edu  <br>
Project Link: https://github.com/datasciencetemple/Trends  <br>

We look forward to your contributions and the opportunity to work together on this exciting project.


