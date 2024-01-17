# Module_4_challenge

A WHALE OFF THE PORT(FOLIO)

This assignment asks to take the returns of some notable investor whales' funds, algorithmic trading systems, S&P 500, and a custom portfolio. I begin by taking the returns of the whales, algorithms, and S&P and combining them into a signle dataframe. I then begin analysis on this dataframe. The first type of analysis I do is performance analysis where I plot regular and cumulative returns. I then move on to risk analysis where I calculate and analyze standard deviations, rolling standard deviations, correlation and sharpe ratios of all portfolios, and the Beta of a chosen portfolio--I chose Algorithmic 1. I found that the Algo 1 portfolio has an average standard devation but extremely high sharpe ratio relative to the rest. This means Algo 1 will outperform all other portfolios while not adding much risk. Algo 1 also has a very low correlation to the S&P 500 which increases diversification. 

The final section of the assignment requires creating a custom portfolio. My portfolio is comprised of Costco, JPMorgan, and Nvidia. I also ran similar analysis on my portfolio as I did previously. I calculated standard deviations, correlation, Beta, and sharpe ratio. I found that my portfolio actually can outperform the Algo 1 portfolio given it has a slightly higher sharpe ratio. Unfortunately, my portfolio does have the highest standard deviation which explains the wild returns and makes it a bad choice for risk adverse investors. 


CODE SOURCE

Most of the code (analysis, concatenating, plotting) was derived from class activities. I also worked with Kimberly Rodriguez. She received tutoring more than once and relayed the information to me, so I suppose I indirectly received tutoring as well. This helped mainly with Beta; I had a ton of trouble calculating it. It turns out I was not using the correct covariance and variance. 


TECHNOLOGIES

There are no major technologies used in this assignment. It was done with Python coding language and used the pandas, numpy, seaborn, and matplotlib libraries. 