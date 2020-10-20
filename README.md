# Obfuscated Text Classification

We have a multiclass text classification task, where the text is obfuscated. In fact, We have three text files: xtrain.txt, ytrain.txt, xtest.txt. Each line in xtrain.txt and xtest.txt comes from a different novel. In total, we have 12 novels, i.e., target classes. The data has been obfuscated, however the patterns in them are preserved. The novel ids corresponding to xtrain.txt are specified in ytrain.txt. 

We first address this task with a traditional text classification pipeline. Then, we train a deep neural network to achieve higher effectiveness. 