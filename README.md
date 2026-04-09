# Overview

- The purpose behind this program is to get a better understanding of data analysis and how to use it to analyze stock data.  I chose to analyze TSLA stock data because I am interested in the stock market and I wanted to see how I could use data analysis to gain insights into the performance of a specific stock.  The data set that I am using is from Kaggle and it contains daily stock data for TSLA from June 29, 2010 to March 24, 2022.  The data includes columns such as Date, Open, High, Low, Close, Volume, and Price Change.
[Kaggle - TESLA Stock Data](https://www.kaggle.com/datasets/varpit94/tesla-stock-data-updated-till-28jun2021)

- The purpose of this software is to analyze the TSLA stock data and gain insights into the performance of the stock over time.  I want to be able to answer questions such as: What are the top 10 days with the highest trading volume and what happened to prices on those days? Which months are most volatile for TSLA stock and are there any seasonal patterns? How has TSLA's performance varied year-by-year?  By answering these questions, I hope to gain a better understanding of how to use data analysis to analyze stock data and gain insights into the performance of a specific stock.

{Provide a link to your YouTube demonstration.  It should be a 4-5 minute demo of the data set, the questions and answers, the code running and a walkthrough of the code.}

[Software Demo Video](http://youtube.link.goes.here)

# Data Analysis Results


1. Overall Question 1: Find the top 10 days with the highest trading volume and analyze what happened to prices on those days?

   1.1 Sub Question: What is the highest volume trade day?
        - Answer: Date: Feb 4, 2020 With a volume of 304,694,000 and a price change of 0.82 which is (0.46%)

    1.2 Sub Question: What is the lowest volume trade day among the top 10?
        - Answer: Date: May 1, 2020 With a volume of 162,659,000 and a price change of -10.74 which is (-7.11%)

    1.3 Sub Question: Do high volume days usually result in an increase or decrease in price?
        - Answer: Out of the top 10 highest volume days, 5 resulted in a price increase while 5 resulted in a price decrease. High volume days do not show a clear tendency to result in either an increase or decrease in price.

    1.4 Sub Question: What is the average volume on the top 10 highest volume days?
        - Answer: The average volume on the top 10 highest volume days is 207,873,070.

2. Question 2: Figure out which months are most volatile for TSLA stock and identify seasonal patterns?

    2.1 Sub Question: Which month is the most volatile on average?
      - Answer: The most volatile month is January with an average price change volatility of 14.48

    2.2 Sub Question: Which month is the most stable on average?
        - Answer: The most stable month is June with an average price change volatility of 4.68

    2.3 Sub Question: Are there any seasonal patterns in volatility?
        - Answer: 
        - Spring (March, April, May) has an average volatility of 8.07
        - Summer (June, July, August) has an average volatility of 5.61
        - Fall (September, October, November) has an average volatility of 9.00
        - Winter (December, January, February) has an average volatility of 13.28

3. Question 3: how has TSLA's performance varied year-by-year?

    3.1 Sub Question: Which year had the highest annual return?
        - Answer: The best performing year was 2020 with an annual return of 731.18%.

    3.2 Sub Question: Which year had the lowest annual return?
        - Answer: The worst performing year was 2022 with an annual return of -11.66%.

    3.3 Sub Question: What is the overall average annual return across all years?
        - Answer: The overall average annual return across all years is: 99.76%



# Development Environment

- This software was developed using Visual Studio Code with the Jupyter Notebook extension. The code is written in Python, utilizing libraries such as Pandas for data manipulation and Matplotlib for data visualization.

The programming language used for this project is Python. The primary libraries utilized include: pandas for data manipulation and analysis and matplotlib for data visualization.

# Useful Websites

* [Kaggle - TESLA Stock Data](https://www.kaggle.com/datasets/varpit94/tesla-stock-data-updated-till-28jun2021)
* [Youtube - Learn Pandas in 30 Minutes](https://www.youtube.com/watch?v=EXIgjIBu4EU)
* [Pandas Documentation](https://pandas.pydata.org/docs/)
* [Matplotlib Documentation](https://matplotlib.org/stable/contents.html)
* [W3Schools - Python](https://www.w3schools.com/python/default.asp)

# Future Work

{Make a list of things that you need to fix, improve, and add in the future.}
* Item 1: I created a single file with the different questions and answers.  I would like to break this up into separate files for each question and answer in the future.
* Item 2: I would like to add more questions and answers to this project in the future.  I only have 3 questions and answers right now, but I would like to add more to further demonstrate my skills.
* Item 3: Right now it only has analysis of TSLA stock data. I would like to create a way that I can easily swap out the data set to analyze different stocks in the future.  This would make it more reusable and allow me to analyze other stocks as well.
