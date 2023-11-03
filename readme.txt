# Team Finlytics Financial Metrics Testing ReadMe

The purpose of this tool is to provide financial analytics for a certain set of companies based on financial parameters like EBITDA, Total Revenue, debt-on-equity ratio, Diluted EPS, etc. Using these fields for the past 3 years we are trying to analyze if the company is in a good position to invest right now and how much return a person can anticipate for that company. 

## Problem Statement

- Lack of financial knowledge in people who want to invest their money in high-return stocks results in inefficient decision-making as they don’t realize the risks and uncertainty associated with it.
- Difficulty in integrating the financial information available, with the financial news due to lack of accessible tools and guidance
- Complexity and inaccessibility of financial data can refrain people from entering the stock market and making informed decisions

# case scenarios 
Case 1 - This is where we captured the data using Bard for the finalized financial matrix and performed analysis on that data to understand if the selected companies are good to invest right now and how much return a person can anticipate. Also, we performed the sentiment analysis and reviewed the latest news trends for that company
Case 2 - In this case we captured the data from a globally known source for financial data - CapitalIQ. We created a clean excel file which had the financial fields for the selected companies and passed that data to PaLM Api to analyze if this is a good time to invest in those companies  and how much return a person can anticipate. Also, we performed the sentiment analysis and reviewed the latest news trends for that company

## File structure - 
1. Google Hackathon Finlytics.ipynb - Python notebook which has all the code for PaLM API, analysis and results
2. Financial_DatabyCapitalIQ.xlsx - Financial data captured from CapitalIQ 
3. case1_final_data_generated_bybard_analysis.xlsx - Contains results based on the data collected using Bard and performed financial and sentiment analysis also based on Bard
4. case2_Bard_analysis_basedon_capitalIQ.xlsx - Contains results based on the data collected using CapitalIQ and performed financial and sentiment analysis also based on Bard

# Results - 
Our preliminary findings indicate that Bard does not consistently provide accurate financial metrics. The discrepancies and inaccuracies found in the data extracted by Bard raise concerns about its reliability for financial analysis.

## Contributors
- Team Name: Team Finlytics
- Team Members: Anoop Kaur, Dakshta Mehta, Megha Maliwal, Saanika Shahi, Sara Rustagi

**Disclaimer:** This project is in no way affiliated with or endorsed by Bard or its developers. It is an independent evaluation conducted by Team Finlytics.

