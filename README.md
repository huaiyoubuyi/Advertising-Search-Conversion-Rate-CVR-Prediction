# project_proposal.md
Alimama Sponsored Search Conversion Rate(CVR) Prediction Contest
Kehao Yao(ky392) Yuan Yao(yy874)

The problem:
The problem origins from Alimama Sponsored Search Conversion Rate(CVR) Prediction Contest, which was sponsored by Alibaba, the largest e-commerce platform in China. 
The conversion rate (CVR) in sponsored search is defined as the probability of a user to purchase the displayed item after clicking this item. CVR indicates customers’ satisfactory to the displayed items, shops and the advertising creative. For example, someone searches “sweater” in Taobao.com on PC or mobile client, dozens of sweaters with different brands and styles will be displayed. By clicking one of these items, detailed information about this item, including the product introduction, store reputation and user comments, will be loaded. Intuitively, if M customers click and browse a specific item, and N of them purchase this item, the CVR of this item is computed as the ratio between the transaction number and the click number, i.e. CVR=N/M.
The dataset:
Here is our dataset 
https://tianchi.aliyun.com/competition/entrance/231647/information

Why the problem is important:
Sponsored search is one of the most popular marketing approaches in today’s internet ecosystem. Merchants (advertisers) set several keywords for their products, and these products will be presented to the customers who search these keywords. 
In sponsored search, if items with higher CVR are displayed, it is much easier for customers to find the satisfied product, which improves the user experience during online shopping. On the other hand, more purchasing behavior is preferable to the advertisers as the return from the marketing budget. In summary, estimating the CVR accurately facilitates the search engines to reach more potential customers, increases the return on investment (ROI) for advertisers, and improves the user experience during online shopping.

Why the data set will allow us to answer the question:
This competition provides massive transaction data of sponsored search in Taobao.com, which are enough for prediction models.
This competition provides 5 tables about clicked samples, advertising items, users, contexts and shops. The clicked sample table provides basic information of clicked samples and trade. The other 4 tables about advertising items, users, contexts and shops provide necessary information for CVR prediction.
The clicked sample table for preliminary consists of samples during several days.
The last day's samples, which is not published to Tianchi user, will be used in the evaluation. The rest data will be provided to train models and tune parameters.
At these tables, there are a few samples lacking specific fields, and the values of these fields will be "-1" in the case.

