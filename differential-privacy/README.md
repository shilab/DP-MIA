# Differential Privacy (DP)
DP measures privacy risk by a parameter ε, called privacy budget, that bounds the log-likelihood ratio of the output of an algorithm under two databases differing in a single individual’s data. Thus ε-differential privacy, a mathematical definition of DP, associates the privacy losswith any data release drawn froma statistical database. If the training model is differentially private with a small privacy budget, the probability of producing a given model from a training dataset that includes a particular record is close to the probability of producing the same model when this record is not included. DP has been used in many machine learning models, including classification, regression, clustering, and dimensionality reduction.