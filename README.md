# Final-Case-Study-Fake-News-Detector


![image.png](http://dojo.electrickettle.fr/files/gimgs/304_MatthieuBourel_Casse-Tete.jpg)

## 1.1 Context


Fake news has been there since before the advent of the Internet.
They are widely accepted to be fictitious articles deliberately fabricated to deceive readers. Social media and news outlets publish fake news to increase readership or as part of psychological warfare.

The latest hot topic in the news is fake news and many are wondering what data scientists can do to detect it and stymie its viral spread.

## 1.2 Objective
Type de diapo

The objective of this notebook and its attached report is to use Machine learning in order to construct a fake news detection algorithm so as to predict if one news is True or Fake and thus study the possibilities of data science in the detection of fake news.
Based on our results, we will be able to develop initial recommendations to any company or organisation that is trying to counteract fake news.


## 1.3 Datasets


Our dataset consists of two parts: a training set and a testing set.
We will use our training set to build our models to predict on the test dataset which articles are considered fake or not.

Each dataset contains 05 variables:

    id: unique id for a news article
    title: the title of a news article
    author: author of the news article
    text: the text of the article; could be incomplete
    label: a label that marks the article as potentially unreliable o 1: unreliable o 0: reliable


## 1.4 Results

Best Models according to accuracy :   
1) 0.971000 	Support Vector Machines   
2) 0.969000 	Stochastic Gradient Decent   
3) 0.9626670 Perceptron
