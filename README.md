# The Russian Election Fraud Bar Crawl

## Introduction

Election fraud is a problem in Russia (citations available upon request), but can we detect it from the publicly available election returns data?

## Some information about the data

Gennady Rudkevich at Georgia College provided a dataset of elections returns going back to 1991. It doesn't include much information, and many feature names may be in Cyrillic.

Some important variable names:
* Year: year of election
* GYear: ruling candidate's share of the vote (Yeltsin, Putin, Medvedev
* LYear: Liberal Democratic Party's share of the vote.
* CYear: Commie share
* TYear: turnout

While the election data is public, the economic data will be provided separately on request, once I get it. This set has thousands of features, including economic variables for that time frame, whether a regional governor has a military/intelligence background, etc. 

## Commentary on detecting fraud from Gennady:

>There are micro and macro ways to catch fraud. The micro version requires looking at precinct level results (which would take quite a long time to enter into a dataset) and then looking at statistical abnormalities, like the distribution of 5s and 0s as the last digit of results, distribution of turnout figures,etc. The macro version means looking at regional results, including correlations between turnout in different elections, the determinants of Putin's support (and turnout) after controlling for various economic and political variables.

The folder names should be fairly self-explanatory.
