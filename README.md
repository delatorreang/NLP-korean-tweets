# NLP-korean-tweets

This is the code and data I used for researching the public perception of freedom of the press in South Korea through Natural Language Processing (NLP) of tweets. I carried out keyword extraction with Term Frequency-Inverse Document Frequency (TF-IDF), topic modeling with Latent Dirichlet Allocation (LDA), and clustering with K-means on a dataset comprising 70,111 tweets.
### Dataset and preprocessing
For obtaining the dataset, I scraped posts by keywords and combinations of keywords with the Twitter module of [snscrape](https://github.com/JustAnotherArchivist/snscrape), and deleted duplicated and unrelated tweets. For tokenizing, I used option okt.nouns of the Python package for NLP of Korean language [KoNLPy](https://konlpy.org/en/latest/). I study treated as stopwords some terms (i.e "마스토돈" [Mastodon], "플로리다" [Florida]) that appeared in the results and were not related to the research topic.
