# SENTIMENT ANALYSIS master thesis
Code and datasets employed for master's thesis

## Abstract 
This thesis paper provides an overview of sentiment analysis and its applications in social media data analysis with a particular focus in influencer marketing. Broadened polarity sentiment analysis is introduced to categorize 25 thousand comments of Kardashian-Jenner sisters' posts in five sentiment intensities. It is found that the strongly positive class is prevalent accounting for more than half of the sample, while the presence of negative and strongly negative comments is minimal. Additionally, a hybrid approach combining lexicon and machine learning methods is employed for broadened polarity sentiment analysis. Random forest with TF-IDF test vectorization is the classifier that performed better performance with a 84\% of accuracy.

Key words: NLP · SA · hybrid approach · VADER · ML · Naive Bayes · Support Vector Machine · Random Forest · Influencer marketing · Instagram.

## Code programs
- 0.1preprocessing : cleans comments and selects English comments and those conveying sentimet.
- 0.2polarity : detects broadened polarity sentiment analysis, i.e. classifies comments in strongly positive, positive, neutral, negative, strongly negative. Note that some changes were performed to the VADER lexicon to adapt it to 2024 Instagram usage.
- 0.3preparation : removes stop words and lemmatizes the comments to prepare them to train ML classifiers.
- 0.4MLresults-BoW : vectorizes comments with BoW and trains and tests NB, SVM, RF.
- 0.4MLresults-tf : vectorizes comments with TF-IDF and trains and tests NB, SVM, RF.
- 0.5results : summarizes the results from broadened sentiment analysis.
