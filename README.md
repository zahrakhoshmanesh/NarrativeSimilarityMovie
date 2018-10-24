# Narrative Similarity

In this tutorial, I am going to explain how we can measure similarity between two movie plots. The problem is really interesting and has many useful applications. One of it's application is finding the similar movies and recognizing remake movies. The base paper we started to work on, is "Where have I Heard this Story Before?: Identifying Narrative Similarity inMovie Remakes" which you can find it [here](http://aclweb.org/anthology/N18-2106).

 - first we need to represent the plot or summary of movie such that make the calculations easy. The best technique is using word embedding. Here, we use word2vec word embedding model developed by Google.  
