Assignment

Thanks for your interest and taking your time to work on the set of exercises below. We thought that exposing you to some of the real life questions we work on would help us understand your skillset better.

Please push your answers (and the code) onto your Github and send us a link to it when you are done. We prefer you to write the code in Python or R -in that order-. We want to give you ample time to work on the problems, but the assignment should not take more than a day.

We hope that you will find the process challenging and fun! Let us know if you have any questions.

1) Data Wrangling, Connecting Datasets

The exercise is a slightly modified version of a recent problem we worked on. Please find the data in the data folder.

test_names.csv
train_names.csv

We are interested in finding the top 10 individuals in the test set who are location-wise closest to the SumAll office. The exercise should follow a two-step process:

	Match the names in the test set to names in training set.

	Geocode the addresses for the matching names and apply a simple distance function to find the closest matches.

2) Data Exploration

The dataset contains a subset of tweet data related to the conflict in Syria.

https://www.dropbox.com/s/wo6zqju6hv7nnx3/tweets.json.zip

We want you to simply count the number of tweets for each day and visualize it using the tool of your choice.

As an example the visualization we put together is below:

http://sumall.org/syria

3) Data Modeling

With this exercise, we expect you to create a feature space and make predictions.

Adapted from a Kaggle competition, the challenge is to detect when a comment from a conversation would be considered insulting to another participant in the conversation. The data consists of a label column followed by two attribute fields. The relevant training and test files are:

train_insult.csv
test_insult.csv

This is a single-class classification problem. The label is either 0 meaning a neutral comment, or 1 meaning an insulting comment (neutral can be considered as not belonging to the insult class. Your predictions must be an integer.The first attribute is the time at which the comment was made. It is sometimes blank, meaning an accurate timestamp is not possible. It is in the form "YYYYMMDDhhmmss" and then the Z character. It is on a 24 hour clock and corresponds to the localtime at which the comment was originally made.The second attribute is the unicode-escaped text of the content, surrounded by double-quotes. The content is mostly english language comments, with some occasional formatting.

Please submit your predictions (0 or 1) in a csv format. Make sure that your submission has exactly 2000 entries.
