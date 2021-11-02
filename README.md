# Parsiq Bounty

## Eth top accounts dynamic index

This project analyzes the money flow of the top 5.000 eth addreses. 

The hypothesis is that there is a relationship between the price of the asset and the flow of money in this group. That should be of particular interest to develop trading strategies or insights abut ETH price behaviour.

###### Only running the query during several weeks, and reviewing the data again, we should evaluate the usefulness of the idea for trading strategies.

PARSIQ DATA: All the eth transactions has been recorded through Parsiq "Triggers and Transports". The data has been collected in two periods (with a gap of one day) due to the limitation of the parsiq trial account.

The analysis has been realized using Julia language and Pluto(Julia notebooks)

1.- A static view of the notebook is available in the TopAccountsDynamicIndex.pdf
2.- A working version is provided using ngrok link: www.google.com
3.-  all the data files are included in the repository.

The project shows a "offline version" of Parsiq data. It is possible to get a online version trought a web hook and run the following code online. But in this notebook I have copied the telegram events to a file in order to provide an analysis without waiting for new data.
