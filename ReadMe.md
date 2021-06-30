# Genre2Vec

## Contents

1. [genre_raw notebook](genre_raw.ipynb) -- Using the basic cardinal data in `data_by_genre.csv`, create crude "vectors" and see if genres are relationally close to intuitively similar genres. (Spoiler: they're not)
1. [genre2vec notebook](genre2vec.ipynb) -- Walk through of the genre2vec model, from tokenization to training.
1. [vec_analysis notebook](vec_analysis.ipynb) -- Analysis of resulting vectors from genre2vec model. Exploration of distances between vectors and some vector functionality. PCA visualization of genre spatial relations.
1. `/fit_vectors/` -- contains fit vectors data from genre2vec model
1. `data` -- raw data from kaggle spotify datasets

## About

genre2vec model follows a similar word2vec model laid out by tensorflow. Approach looks at what genres typically show up with other genres (in `data_w_genres`) instead of related genres by musical characteristics.

*Still under construction*