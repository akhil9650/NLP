# NLP

[NLP Data Processing](https://github.com/akhil9650/NLP/blob/main/nlp_data_processing.ipynb)

The data([skillege.csv](https://github.com/akhil9650/NLP/blob/main/skillege.csv)) used here lists skills scraped from LinkedIn on 92000+ profiles. Skills are transformed from list based format to one that is accepted by Word2Vec library. This text processing is necessary because this is the format Word2Vec is able to work on to create word embeddings.
This is used in the subsequent notebook

[Word2Vec](https://github.com/akhil9650/NLP/blob/main/word2vec.ipynb)
Prepared dataset is used and a Word2Vec model is trained on it. Results of this model are to group together similar skills. 
So, if a person has listed 'Software' as a skill, as expected the trained model points out that 'Information Technology' is also a relevant skill and you're likely to find the 2 skills on one profile regularly.

The real world use case of using this model and dataset as depicted here is to develop another approach for recommendations, or in simpler terms 'If you liked this, you'll also like' section that is a part of so many content-offering websites.

FURTHER READING:
https://towardsdatascience.com/introduction-to-word-embedding-and-word2vec-652d0c2060fa
