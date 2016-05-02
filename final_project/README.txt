CS591 Final Project
Corey Clemente & Renzo Callejas
1 May 2016

In the IPython file, there are 5 cells. 

The first 3 cells are the three steps to the project and do not execute anything when run. They simply load all the necessary functions. 

The 4th cell shows the function we “ran” to do our project. It simply defines the 8 companies we chose (and their stock codes), downloads the number of tweets we specified, parses them and does sentiment analysis, creates the training data, trains the models, and shows the results. DO NOT RUN THIS (unless you don’t mind letting the project run, which takes about 17 hours in its entirety if Twitter doesn’t block your IP).

To see the results of our project, simply rum “see_results_of_project()” in the 4th cell. 

The 5th cell lets you create your own “mini” version of the project, where you can define a few companies, a small amount of tweets to gather, and that’s it! Simply change the defined variable to your liking and run the cell. It will scrape the tweets, run sentiment analysis, and try and predict the stocks using that data. (Essentially, we include this so you can see all of the exact steps taken).

Thank you!

SCRAPER:

We got the twitter scraper from github here:

https://github.com/Jefferson-Henrique/GetOldTweets-python