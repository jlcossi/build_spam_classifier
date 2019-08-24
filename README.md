
# Introduction

Spam detection is one of the major applications of Machine Learning in the interwebs today. Pretty much all of the major email service providers have spam detection systems built in and automatically classify such mail as 'Junk Mail'. 

In this project we will be using the Naive Bayes algorithm to create a model that can classify SMS messages as spam or not spam, based on the training we give to the model. It is important to have some level of intuition as to what a spammy text message might look like. Usually they have words like 'free', 'win', 'winner', 'cash', 'prize' and the like in them as these texts are designed to catch your eye and in some sense tempt you to open them. Also, spam messages tend to have words written in all capitals and also tend to use a lot of exclamation marks. To the recipient, it is usually pretty straightforward to identify a spam text and our objective here is to train a model to do that for us!

Being able to identify spam messages is a binary classification problem as messages are classified as either 'Spam' or 'Not Spam' and nothing else. Also, this is a supervised learning problem, as we will be feeding a labelled dataset into the model, that it can learn from, to make future predictions. 

# Results

Accuracy score:  0.9885139985642498.  
Precision score:  0.9720670391061452.  
Recall score:  0.9405405405405406.  
F1 score:  0.9560439560439562.  

# Overview

For learning purpose, this project has been broken down in to the following steps: 

- Step 0: Introduction to the Naive Bayes Theorem
- Step 1.1: Understanding our dataset
- Step 1.2: Data Preprocessing
- Step 2.1: Bag of Words(BoW)
- Step 2.2: Implementing BoW from scratch
- Step 2.3: Implementing Bag of Words in scikit-learn
- Step 3.1: Training and testing sets
- Step 3.2: Applying Bag of Words processing to our dataset.
- Step 4.1: Bayes Theorem implementation from scratch
- Step 4.2: Naive Bayes implementation from scratch
- Step 5: Naive Bayes implementation using scikit-learn
- Step 6: Evaluating our model
- Step 7: Conclusion

# Installation
1. [Download and install Conda](https://docs.conda.io/projects/conda/en/latest/user-guide/install/macos.html). I suggest Miniconda which is quick and easy

2. Install all the other dependencies using the "environment.yml" file included :
```
${HOME}/miniconda/bin/conda create -f environment.yml
```

3. Activate the new environment as suggested by conda
```
${HOME}/miniconda/bin/conda activate spamclassifier
```

4. launch jupyter using the notebook
```
$ jupyter-notebook spam_classifier.ipynb
