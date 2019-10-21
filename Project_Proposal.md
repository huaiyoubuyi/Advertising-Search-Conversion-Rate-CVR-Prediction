# project_proposal.md
Advertising Search Conversion Rate(CVR) Prediction 
Kehao Yao(ky392) Yuan Yao(yy874)

Initiative: 
In the era of Internet, online shopping becomes increasingly popular among people in our generation. When shopping on e-commerce platforms like Amazon, if we search a specific item, for example, sweater, dozens of sweaters advertisements with different brands and styles will be promoted. That makes us wonder whether this advertising strategy is effective, and what kinds of factors will finally influence a target customer’s purchase decision.

Problem Statement:
Given the information about the advertising items, target users and item providers, what is the probability that the target users will finally decide to buy the advertising item?

The problem origins from Advertising Search Conversion Rate(CVR) Prediction Contest, which was sponsored by Alibaba, the largest e-commerce platform in China. The conversion rate (CVR) is defined as the probability of a user to purchase the displayed item after clicking the advertisement. Intuitively, if M customers click and browse a specific item, and N of them purchase this item, the CVR of this item is computed as the ratio of the number of transaction and click, i.e. CVR=N/M.

Dataset:
Here is our dataset 
https://tianchi.aliyun.com/competition/entrance/231647/information

This dataset is provided by Alibaba and contains over 500,000 advertising data. Our data mainly include five different aspects, which are basic information, advertising items, target users, contexts and merchants. 

With these information, hopefully, we will be able to predict how likely is a customer to buy the advertising item after watching the advertisement provided by the platform. We are going to separate our dataset into three parts. The first 80% of the shuffled data will be used as our training set, the following 10% validation set and the last 10% testing set.

Significance:
Sponsored search is one of the most popular marketing approaches in today’s e-commerce ecosystem. Merchants (advertisers) set several keywords for their products, and these products will be presented to the customers who search these keywords. 

CVR indicates customers’ contentment to the displayed items, merchants and the advertisement itself. If items with higher CVR are displayed, it is much easier for customers to find the satisfied product, which improves the user experience during online shopping. On the other hand, more purchasing behavior is preferable to the advertisers as the return from the marketing budget. 

In summary, accurate estimation of the CVR facilitates the search engines to reach more potential customers, increases the return on investment for advertisers, and improves the user experience during online shopping.

