![alt text](https://github.com/ktcraig/Project-1-AI-Class/blob/main/Money%20Miners%20Header.png)


**Team Members**: Katie Craig, Sowmya Shetty, Matthew Ward, Joel Freeman, Pablo Romero, Roderick Burroughs

**TA**: Rimi

# Summary:
This repository is the team Money Miner's Project 1 Class Repository. This is the public, group repository to organize our challenge about Project 1.

This repository contains:

1) Project Requirements

2) Project Code

3) Source Code References

4) Final Presentation

# Download instructions:

Download the following files to run the notebook:

Code File: **Money Miners.ipynb** Main Branch Notebook

Data CSVs for resources: **Bitcoin_Data.csv**, **SP500_Data.csv**, **Gold_Data.csv**

# Presentation:

Filename (Google Slides): "**Project_1_MoneyMiners_Investment_Forecasts_Final.pptx**"

# Project Overview and Research questions to answer:
While working for a large equity-trading company, you’re tasked with researching next steps for a client’s portfolio. Your client is unsure of where they should invest, Bitcoin, Precious Metals or an Index Fund, and needs expert analysis to make the right decision. Using S&P 500 data from 2019 to 2024, we will analyze the current stock prices and which investment will yield the highest return while using the Prophet model. 

Our research questions to answer:

1) What is the forecasted value of Bitcoin for 1 year from now?
   ```diff
   The value of Bitcoin is forecasted to be $124,964.108004 on 12/29/25 (ythat)
    ```
   
2) What is the forecasted value of Precious Metals (Gold) for 1 year from now?
   ```diff
   The value of Gold is forecasted to be $3460.329886 on 12/29/25 (ythat)
    ```
   
3) What is the forecasted value of Index Fund (SP500) for 1 year from now?
   ```diff
   The value of Gold is forecasted to be $7522.829784 on 12/29/25 (ythat)
   ```
   
4) Which fund would you recommend for the **highest yield** in 1 year:
   ```diff
   We would recommend Bitcoin for the highest yield at the end of the year; however, the beta for bitcoin was 1.0284655818228168, making it the riskiest stock out of the 3 we analyzed.
   ```
   
5) Which fund would you recommend for **lowest risk** to return on investment in 1 year: **Bitcoin, Precious Metals, or an Index Fund**
   ```diff
   We would recommend Gold for the lowest risk at the end of the year due to the beta for gold being 0.07232706930965804 which made it the least risky stock compared to SP500.
   ```

# Datasets(s) to be used:

1) Data Bitcoin Price: https://www.investing.com/crypto/bitcoin/historical-data

2) Gold Price: https://www.investing.com/commodities/gold-historical-data

3) S&P 500 Data: https://www.nasdaq.com/market-activity/index/spx/historical

# Resources:

The following resources were used in the analysis of this project:

**Panda functions** For pip installing prophet, datetime, matplotlib, gdown, pyplot, hvplot, google.colab, and numpy

hvplot:  https://hvplot.holoviz.org/

gdown:  https://ctshizubu.medium.com/download-data-from-anywhere-into-google-colab-using-gdown-eb6ab383875c

**ChatGPT** For assistance on calculating beta values

**Stackoverflow** For references to formatting readme and markdowns


# Summary Analysis:

We analyzed the price of each stock from 2019 to 2024 to identify trends and load the data into the Prophet model to forecast the future. Bitcoin was the leader of price in 1 year at the end of 2025 with a value of $124,964.10 on 12/29/25 (ythat value). Calculating the price over time was the easy part though. Practically, it was easy to tell that Bitcoin would answer our first question of the highest return in 1 year for our client. We created a base notebook for bitcoin to compare price over time, calculate stock volatility and then visualize the differences graphically. We then copied this notebook for Gold and SP500 data and modified respectively for the differences in data. We still struggled with quantifying how volatile a stock was though. This is where we investigated Standard Deviation, Average True Range and Beta which we will explore in our recommendations.Using SP500 as the benchmark, we quantified the beta values for bitcoin and gold respectively. This will give our client a quantifiable value for what is the riskiest stock versus only looking on stock volatility. The beta for gold was 0.07232706930965804 which made it the least risky stock compared to SP500. The beta for bitcoin was 1.0284655818228168, making it the riskiest stock out of the 3 we analyzed.

To visually display our findings, see our plots and hvplots in our Money Miners.ipynb document.


# Project Requirements:
**Requirements**

**Software Version Control (10 points)**

Repository is created on GitHub (2 points).

Files are frequently committed to the repository (3 points).

Commit messages include an appropriate level of detail (2 points).

Repository is organized and includes relevant information and project files (3 points).

**Documentation (10 points)**

Code is well commented with concise, relevant notes (3 points).

GitHub README file includes a concise project overview (2 points).

GitHub README file includes detailed usage and installation instructions (2 points).

GitHub README includes either examples of the application, or the results and a summary of the analysis (3 points).

**Analysis and Conclusion (30 points)**

Findings are strongly supported with numbers and visualizations (10 points).

Write-up summarizes major findings and implications at a professional level (10 points).

Each question in the project proposal is answered with precise descriptions and findings (5 points).

Each question response is supported with a well-discerned statistical analysis from lessons, such as aggregation, correlation, comparison, summary statistics, sentiment analysis, and time series analysis (5 points).

**Visualizations (20 points)**

6–8 visualizations of data (at least two per question) (10 points).

Clear and accurate labeling of images (5 points).

Visualizations supported with ample and precise explanation (5 points).

**Presentation Requirements (30 points)**

Your presentation should cover the following:

An executive summary or overview of the project and project goals (5 points).

An overview of the data collection, cleanup, and exploration processes (5 points).

The approach that your group took in achieving the project goals (5 points).

Any additional questions that surfaced, what your group might research next if more time was available, or share a plan for future development (5 points).

The results and conclusions of the application or analysis (5 points).

Slides effectively demonstrate the project (3 points).

Slides are visually clean and professional (2 points).




