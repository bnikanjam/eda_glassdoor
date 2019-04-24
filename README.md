# Exploratory Data Analysis of:
# Microsoft, Apple, Amazon, Google, Netflix, and Facebook Workplace Reviews
## by Babak Nikanjam


## Dataset

> We have over 67,000 reviews for Google, Amazon, Facebook, Apple, Netflix, and Microsoft. The dataset is hosted on Kaggle and is scraped from www.glassdoor.com. The raw data set was untidy. Location, Job Title, Current or Past Employment, and Anonymity was extracted from existing columns according to the principles of tidy data. 

> This dataset is a fraction of what can be easily found on glassdoor.com which already provides so much information about each company. We are not going to focus on answering trivial questions similar to what company has the highest ratings. We like to find the pattern between what matters to employees regardless in general.


## Summary of Findings

> The employees and senior management relationship shows it is the most troubling. This goes hand in had with work-life balance with very similar distribution pattern. One main insight to take home here is the better the relationship between teams and their management the work feels more like life or time spent in worthy way.
> Not only those employees with a negative experience are more vocal in general, but past unhappy employees also seem to be more so than current employees.


## Key Insights for Presentation

> Our work and workplace are a big part of our lives, and often they become a significant factor in our identities. In exploring our data set that is scraped off of popular job review site, glassdoor.com, we wanted to see how different things that matter to employees relate to each other. To do so, we only use reviews within the US, Canada, Irland, and the UK to have a reasonably similar workplace similarity yet diverse enough to consider as many people as possible. We could focus on comparing different regions of the world together for example how employees experience stack up against each other between the US and India. We could also separate employees based on their job titles into two general groups of Engineering and Production vs. Retail, and Administrative jobs. To answer our main question here, after some trial and error we realized it is best to consider all type of employees' ratings together.
Here we plot the mean of each one of the other five-stars rating group against each level of the Overal-Rating. We can see that the lower the Overall-Ratings, the wider of a gap between the Compensations-Benefit. In other words, For employees who were most negative about their workplace experience, money was the least important factor, and as the plot clearly shows below, those employees on average were relatively not troubled with their pay as to the other factors. This finding also holds even when we distinguish anonymous employees and or current or past employees.