The data is motivated by Google analytics. Your job is to predict REVENUE.

DOMAIN CONTEXT:

Just to summarize what I said in class about SEO/SEM internet monetization. Here, you have a web site which is selling, say, baseball hats.  You want to know who is buyin? Should I  buy more google ads? Pay some SEO expert? You want to make more money obviously - sell more hats or more clicks on ads on your site.  First of all you install (free) Google Analytics (GA). GA montors tons of attributes about your users, literally dozens of features, including geo-information, some approximate personal data,  may be even your users personality types :-). Our data is just a toy example subset of what you get in GA.

So:

People may either come to your web site  directly  (know the link, put it in the browser) or find it through google search or google sponsor links. It is probably less likely that they will buy your hat if they get to your web site through regular google search since they may be looking for something else, and your SEO guy (search engine optimization) has outsmarted google and managed to engineer your site to show up in top 10 for a query "data analytics tools". You may have also bought sponsored link from google for specific adwords (say "data tools", "hats") and users may have arrived to your site from such sponsored link. Again, they may be mislead  and looked for somthing else, and some may buy or click on ads on your site, others may not.

But....it may also be the case that users searched for your site on Google and found it using search.  Google analytics would actually show you the keywords users used to get to your site. We do not show it here. So, it may happen that someone comes from Google search to your site and is a motivated buyer of your hat.

Data like the one which we simulated is very important in the monetization of web sites.  This data would tell you whether to spend money buying ads from google? Or hire a good SEO guy.  Lots of jobs these days amount to analyzing Google Analytics data to maximize web sites profit.

This is why -although the data is simulated, it is very practical situation where data analysis is the key.

Attribute meaning:

DURATION - duration on user session on your web site
ACTIVITY -  how many links did the user clicked on your site
SOURCE - how did the user find your site - through google search? by clicking on google sponsored links (which you paid for), or by going directly to your site from the browser (i.e. typing the url)
REVENUE - how much money did this user make you (i.e your web site, by either buying something or clicking on ads on your site)

You can use any ML software from R library, you can use several packages from recitations - like random forest or svm. But no restrictions. of course you can use rpart or lm (linear model, per recitation slides)

Notice we are predicting NUMERICAL variable, not categorical like before. we will use MSE (Mean Square Error) to rank your results.


The testing file will be provided later, before Wed.  The new Kaggle rules will also be imposed which are much closer to reality. That is we will not show the ranking or your error before midnight on Thursday.  The only basis of your decision to submit should be crossvalidation on the training data. Not the other students scores, nor repeated submissions. Last submission will count (if you submitted twice)

If TOP SCORES are the same, the winners will be determined by the time of submission. The top 2 will be provided with small bonuses only if tied.
TBD.



