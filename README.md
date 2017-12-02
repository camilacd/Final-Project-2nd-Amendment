# How mass shootings polarize gun control debate in the US
### **Final Project PPHA 30550** Introduction to Programming for Public Policy

Students: Camila Carrasco (@camilacd), Lina Pedraza (@linapp), Evelyn Sanchez (@EvelynaS)

Date: December 1, 2017

* The code used can be seen in [Final Code](https://github.com/camilacd/Final-Project-2nd-Amendment/blob/master/Mass%20Shootings%20and%20Social%20Media.ipynb)

* The first proposal submitted on October 31st is described in [First Proposal](https://github.com/camilacd/Final-Project-2nd-Amendment/blob/master/Proposal_Oct31.pdf). At first, the idea was to focus on Las Vegas shooting, but it was changed to the Texas shooting due to data availability.

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
We found that on average 19.57% was positive, 10.74% was negative and 69.68% was neutral. We plotted the number of tweets under each category to see their evolution. It should be highlighted that these results should be intepreted carefully since those classifiers are not always accurate and they have some limitations when irony, or other complex structures are in place.   Finally, using the library **Wordcloud** we tried to plot the most common words, but we're unable to retrieve the result. 

- **PART 3: Analysis of the gun stock market in the aftermath of the shooting in Texas**

In this section we explore the behavior of the gun stock prices around the period of the mass shooting in Texas and Las Vegas. For this purpose, we will use the stock price of one of the most important gun companies in the US- RGR and we will try to find how the mass shooting impacted its stock's price. We did not find evidence that a mass shooting has an impact on the price of RGR. We do find that the gun stock market responds to the context of the overall market rather than to an event of shooting.

It is important to note that we will only use graphical analysis to study this correlation. Our initial approach was to explore if the volume of tweets related to the Mass shooting in Texas was a determinant of the price of the stock RGR. However, we did not have enough hourly data on the stock's price (since the stock market trades only 7 hours a day) and we only had 2 days of tweets data after the shooting.

