Twitter-Gnip-Stream
===================
This Demo is build as a early version Prototype for ReduceData Inc http://www.reducedata.com/

This Demo collects large Datasets from Gnip Twitter Stream and uses MySql as the backend Database.



Getting Started with Gnip : http://support.gnip.com/

Repostiory Description:

*Package Gnipparser has a server that would connect to the Gnip stream and read the Json data and the parser would parse the Json, pulls the required data and writes them to a  MySql Database.

*Package TwitterBrowser is a Play framework repository that reads the required values from the Json data that is fed into the MySql database and renders the insight on the fetched data in the form of the listed below charts - 

1) Line chart -- Tweet Vs Retweet comparison
2) Stacked Bar chart -- Tweet Vs Retweet Funnel
3) Pie chart -- Anyalysis on the Platform where the Tweets Came from
4) Geo Chart -- Geo mapping based on the origin of the tweets.


Note:  Server and Parser are in the early versions and it cannot handle large datasets, subsequently gnip might forcefully disconnect the stream if the bandwidth fails to meet the flow in of large payloads.

