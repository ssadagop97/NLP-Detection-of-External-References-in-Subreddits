# NLP-Detection-of-External-References-in-Subreddits

Module 1: Introduction and Problem Statement

Reddit is a website where things like web content rating, social news aggregation and discussion takes place. The users can post content like links, images, etc. and then vote up or down for the posts put up by other users. Users can also comment on the posts posted by other users. We intend to study these submissions and comments to analyze the external sources present in these comments. 
A model to predict whether a given text contains would be useful in many situations such as finding references in journals or papers, cross-referencing, etc. where we validate the presence of external sources to make sure the data is original. We can in turn use this to figure out truthfulness or validity of a text by calculating the number of external references cited. We can detect fake news through this algorithm too (If there are no supporting evidence for a given text).
Major Objectives:

1.	In this project, we will explore computational techniques to automatically identify if a given Reddit submission(comments) contains external sources or not. We will use the given sample dataset of Reddit submissions, to analyze the texts and build a supervised learning classifier

2.	We conceive this as a classification problem where we would be classifying our text as containing an external source (1) or not containing an external source (0). We would be devising multiple feature sets- Unigram /bigram and a set of extra features. We would be exploring multiple classification algorithms and coming up with the best performing model to score our data set.

3.	To create a Rule Based external references extractor. We would be using it as another Y variable to build another set of predictive models.

4.	To compare the performances of all the models built and come up with a single best combination of the feature set, Y variable and the algorithm combination.
