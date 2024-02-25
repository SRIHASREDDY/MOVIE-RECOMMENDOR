TYPES OF RECOMMENDATION SYSTEM:
1.CONTENT BASED
-based on tags
-based on content similarity
2.COLLABORATIVE BASED
-users interset
3.HYBRID


CURRENT PROJECT IS BASED ON CONTENT BASED RECOMMENDATION SYSTEM

STEPS THAT TAKES PLACE:
1.data
2.preprocessing
3.model building
4.convert to website
5.deploy

AIM:MY PROJECT IS A MOVIE RECOMMENDER

DATASET:TMDB 5000 Movie Dataset Downloaded from KAGGLE

PROCESS:

PHASE-1:

1.manuplate the data 
2.create tags for the dataframe by merging some of them and crating a db

PHASE-2:

1.apply vectorization
2.convert text to vectors(we are using bag of words. There are tfidf,word2vec)
3.apply steming (to remove duplicate letters)
4.instead of euclidean distance find nearset dist using cosine angle 