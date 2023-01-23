# Text_Clustering
Performed Text Clustering on Food Reviews
Downloaded the fine foods dataset from:
http://snap.stanford.edu/data/web-FineFoods.html
Performed the following tasks:
• Identifed all the unique words that appear in the “review/text” field of the reviews. Denoted
the set of such words as L.
• Removed from L all stopwords in “Long Stopword List” from http://www.ranks.nl/
stopwords. Denoted the cleaned set as W .
• Counted the number of times each word in W appears among all reviews (“review/text” field)
and identify the top 500 words.
• Vectorized all reviews (“review/text” field) using these 500 words (see an example of vec-
torization here: https://bit.ly/3CcY9i4).
• Clustered the vectorized reviews into 10 clusters using k-means. This will give you 10 centroid vectors.
• From each centroid, selected the top 5 words that represent the centroid (i.e., the words with
the highest feature values)
