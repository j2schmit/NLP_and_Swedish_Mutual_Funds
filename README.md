# NLP_and_Swedish_Mutual_Funds
Classifying mutual funds through the use of text mining and NLP.

A fintech startup I've been working with needed a sort of recommender system for financial products such as mutual funds. The startup is focused on Scandanavia, so as I began to webscrape various Scandavian financial institutions I noticed a large amount of irregularity. This irregularity ranged from using abbreviations for a fund name versus using the full name to having multiple names for the same category. 

I want to find a better way to assign a category to each mutual fund that is not dependent upon the category assigned by a given institution. I've recently been reading up on text mining and NLP, which has been one of the great successes of deep learning. Perhaps nothing more than tf-idf analysis could help to better categorize these mutual funds. Other options may be Latent Semantic Analysis or word2vec, but it should be noted that the fund information is not in English. Word2vec would require a well-trained model for Swedish, which at the moment I haven't looked for, by some simple text mining andbasic NLP may be sufficient for this task.

This repository explores this possibility.
