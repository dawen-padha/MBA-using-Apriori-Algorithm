# MBA(Market Basket Analysis) using Apriori algorithm
First let's talk about what is market baket analyis and how we could implement that concept using one of the Association 
rule algorithm.

**Market Basket Analysis:** It is a data miining technique used by large retailers to discover association between items.It works by 
looking for combination of items that occur frequently in transactions. The analysis can help to promote deals , and make good offers.
Market Basket Analysis is modelled on Association rule mining and some of the alogrithms that we can use for MBA are **Apriori and Eclat**.
In Market Basket Analysis, we look to see if there are combinations of products that frequently co-occur in a transaction.



**Apriori Algorithm**: This algorithm is used to calculate association rules between objects. IN other words it looks for the pattern to find out how objects are related to one another. It tells us , person who bought this also bought that, and depending on that rule, retailers can make offers, to increase sales and promote cusotmer satisfication.

The components of Aprori algorithm are:
. Support
. Confidence
. Lift

Support: It has been calculated with the number of transactions divided by the total number of transactions made.

Condidence: It is calculated with combined transactions/individual transactions.

Lift: It is used to find out the ratio of increase in sales, calcultaed as confidence/support.



**Project:** In this project, i have taken a dataset from a retial shop, having list of transactions having transaction id and the names of items that are bought.
After loading and preprocessing the dataset, i have trained the dataset using apriori algo , and then showed the results after training the dataset.
The final result showed the items which are frequently bought together arranged in decreasing order of their lifts.

