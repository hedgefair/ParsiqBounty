# Parsiq Bounty

## Eth top accounts dynamic index
This Pluto notebook (julia language) analyzes the money flow of the top 5.000 eth addreses. 

The hypothesis is that there is a relationship between the price of the asset and the flow of money in this group. 

PARSIQ DATA: All the eth transactions has been recorded through Parsiq "Triggers and Transports". The data has been collected in two periods (with a gap of one day) due to the limitation of the parsiq trial account.

Here, I will show a "offline version". It is possible to get a online version trought a web hook and run the following code online. But in this notebook I have copied the telegram events to a file.

###### Only running the query during several weeks, and reviewing the data again, we should evaluate the usefulness of the idea for trading strategies.

