# **Process**

- The recommender takes methods.csv created in Lab00 as the input.
- The recommender converts the collected java methods to tokens for input to the N-gram model.
- 20000 train data have been used to train the N-gram model and perplexity testing is done on 4000 test data. 1000 data items marked as test have been used for sampling purposes and the result has been shown in outputs.json file.
- The code defines a class NGramModel for the N-gram model which enables the calculation of perplexity, probability and helps to sample the model.
- First we take some arbitrary values of N and calculate the perplexity based on training on the train set and tesing it on the test set.
- The results of the test perplexity helps us decide the most suitable value of N for the given data.
- The model was then initialized using the best value of N and then the sampling dataset was sampled.
