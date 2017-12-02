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

One remarkable and unexpected outcome of project, was found in the analysis of the most active twitter users (the ones who twitted the most), in which is possible to observe that the top 10 most active users are fake accounts (bots), designed to spread pro-gun messages or promote the membership and support to the National Rifle Association (NRA), the most famous non-profit organization that advocates for gun rights in US. 

Moreover, it is interesting to observe that while some of this fake user tweeted the same message several times, others made small modifications to the text or tweeted completely different messages. It is difficult to estimate the number of fake accounts created for this propose, nevertheless according to the text analysis 112,55 tweets contained the word “NRA”. These tweets could had been generated from different fake accounts that promote the NRA or gun rights. 

Contrary to this position, the most retweeted tweed (63,365 RT), from a real user, presents an anti-gun rights position. This single tweet represented 38% of the total number of tweets in our study. Finally, it is important to notice that only 514 tweets contain the word terrorist, even though during Las Vegas shooting (Oct. 1, 2017), almost one month before, this word was often used by the media to describe the attack.

One of the limitations that we found was the impossibility to track the geographical location of the twitter users. This difficult derives that the fact that many users do not report their location or report unprecise or fictitious location (such as “my house” or “Wonderland”). Having better information about the location of the users would had allowed us to explore the presence of geographical relation with and pro or anti-gun rights attitude or its relation with the a specific political preference

- **PART 2: Sentiment Analysis in Twitter**

Using the library **TextBlob**, we classified the tweets in positive, negative and neutral. 
We found that on average 19.57% was positive, 10.74% was negative and 69.68% was neutral. We plotted the number of tweets under each category to see their evolution. It should be highlighted that these results should be intepreted carefully since those classifiers are not always accurate and they have some limitations when irony, or other complex structures are in place.   Finally, using the library **Wordcloud** we tried to plot the most common words, but we're unable to retrieve the result. 

- **PART 3: Correlation between number of tweets and gun stocks**
