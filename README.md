# How mass shootings polarize gun control debate in the US
### **Final Project PPHA 30550** Introduction to Programming for Public Policy

Students: Camila Carrasco (@camilacd), Lina Pedraza (@linapp), Evelyn Sanchez (@EvelynaS)

Date: December 1, 2017

* The code used can be seen in [Final Code](https://github.com/camilacd/Final-Project-2nd-Amendment/blob/master/FinalCode.ipynb)

* The first proposal submitted on October 31st is described in [First Proposal](https://github.com/camilacd/Final-Project-2nd-Amendment/blob/master/Proposal_Oct31.pdf). At first, the idea was to focus on Las Vegas shooting, but it was changed to the Texas shooting due to data availability.

* Additional documentation includes:
  - [stocks](https://github.com/camilacd/Final-Project-2nd-Amendment/blob/master/stock%20prices.xlsx)

IN SUMMARY:

#**1. What are the effects of the Texas Shooting on social media and financial markets?**

In this work we want to assess how an extreme event -like a shooting- affects the discussion about the right to bear arms in U.S. and how it relates with gun stocks. We will characterize tweets evolution regarding the 2nd Amendment, perform a Sentiment Analysis in Twitter assessing if some significant changes occur in the aftermath of the Texas shooting and finally we will study the correlation between the tweets and gun stock prices. 

#**2. Sources**

Twitter database
- We use the streaming API, that allows to filter through tweets in real time.  
- Query: "2nd amendment" + "Second amendment".
- Total amount of tweets: 166.610.
- Dates: Nov, 1st 2017 16:00 - Nov, 7th 2017 07:00.
- More information: https://developer.twitter.com/en/docs/tweets/filter-realtime/overview.html

Yahoo Finance database (* these are some examples of guns stocks)
- Sturm Ruger (RGR)
- Standard and Poor's 500 - S&P 500 (SPX)

#**3. Analysis**

- **PART 1: Analysis over Tweets on 2nd Amendment and Gun Control**


- **PART 2: Sentiment Analysis in Twitter**

Using the library **TextBlob**, we classified the tweets in positive, negative and neutral. 
We found that on average xx% was positive, xx% was negative and xx% was neutral. We plotted the number of tweets under each category to see their evolution. Finally, using the library **Wordcloud** we tried to plot the most common words, but we're unable to retrieve the result.

- **PART 3: Correlation between number of tweets and gun stocks**
