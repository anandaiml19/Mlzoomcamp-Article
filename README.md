<h1 align="center">A Walkthrough on semantic search with sentence transformers

### __👨‍💻__

We humans can identify and categorize similar objects viz., cars and aeroplanes to be grouped into transportation categories. The same can be achieved in NLP tasks through semantic search. It is an Information retrieval technique where the meaning of the word is taken into consideration when a word is looked at in a search engine. For example, if we search for a word, "artificial intelligence" the semantic search can retrieve similar words such as "Deep learning", and " machine learning " which share close similarity to the original word. One way to perform the semantic search is by using a sentence transformer-based model such as all Mini LM _L6 _V2. This model is a pre-trained Transformer model trained on 1B sentence spares. The model maps the input text into 384-dimensional vector space. The corpus text (the text where the search is to be performed ) is passed into the sentence transformer of all Mini LM_L6 _V2 models. The output is stored as the Corpus embedding the 384 dimension vector space. When the user inputs the query text, it is again passed into the sentence Transformer model and it is converted into a query embedding dimensional vector. Now , similarity searches performed between Corpus and query embedding and words with higher cosine similarity are returned as the output text.

<p  align="center"><img width="70%" src="https://github.com/anandaiml19/Mlzoomcamp-Article/blob/main/article.png" /></a></p>

### __👨‍💻Abour Project__

The project deals with the development a Semantic Search and Recommendation System on Quora Question -Answer Data using Sentence Transformer. schematic search it is an Information retrieval technique where the meaning of the word is taken into consideration then your word is looked into search engine. The data set used for this project is given in the below link:


Quora Question-Answer Dataset Link:  https://huggingface.co/datasets/toughdata/quora-question-answer-dataset?row=0
Parquet file format of dataset link: https://huggingface.co/datasets/quora/tree/refs%2Fconvert%2Fparquet/default/train


The datset is preprocessed and the the sentence transformer model distiluse-base-multilingual-cased-v1 is used for the creation of the embeddings of the corpus dataset. Based on the input text from the user the present model is capable to provide similar words or sentennces. Also based on the input question the developed recommedation system can deliver similar questions from the corpus data.

Input Query:

![alt text](https://github.com/anandaiml19/Capstone_Project_2_MLZoomCamp24/blob/main/Query1.PNG)

Semantic Results:

![alt text](https://github.com/anandaiml19/Capstone_Project_2_MLZoomCamp24/blob/main/Results-semantic-search.PNG)






    



