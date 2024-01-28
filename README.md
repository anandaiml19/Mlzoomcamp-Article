<h1 align="center">A Walkthrough on semantic search with sentence transformers

### __👨‍💻__

We humans can identify and categorize similar objects viz., cars and aeroplanes to be grouped into transportation categories. The same can be achieved in NLP tasks through semantic search. It is an Information retrieval technique where the meaning of the word is taken into consideration when a word is looked at in a search engine. For example, if we search for a word, "artificial intelligence" the semantic search can retrieve similar words such as "Deep learning", and " machine learning " which share close similarity to the original word. One way to perform the semantic search is by using a sentence transformer-based model such as all Mini LM _L6 _V2. This model is a pre-trained Transformer model trained on 1B sentence spares. The model maps the input text into 384-dimensional vector space. The corpus text (the text where the search is to be performed ) is passed into the sentence transformer of all Mini LM_L6 _V2 models. The output is stored as the Corpus embedding the 384 dimension vector space. When the user inputs the query text, it is again passed into the sentence Transformer model and it is converted into a query embedding dimensional vector. Now , similarity searches performed between Corpus and query embedding and words with higher cosine similarity are returned as the output text.





