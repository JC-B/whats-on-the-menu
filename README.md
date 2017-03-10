# whats-on-the-menu
DSC6001 project - Statistical Data Science Project

The project loads and combine some of the various bits and pieces of the New York Public Library’s What’s on the menu? dataset.

The data is spread out across a couple of files in the dataset, it’s not as straightforward as we’d like. We’ll have to join data from a few files to get what we want. And, the data cleanse is extensive to be able to make a few limited categories and aggregations to build statistical models on them. Event category data cleanse involves a lot of approximations and match for closest string

The project then deals with fitting some frequency plots, distributions across some categorical features. I tried to fit a linear regression model to the response variable  price of items on menus over different categories like the year of the menu
the event it is served at.

GLM models did not fit very well. The 'paraboli' fit, though an improvement,  did  not really befit the data set

Derived some probabilities using Bayesian Theorem. Hypothesis test that average price for dinner > average price for breakfast was rejected from the p-value based on this dataset
