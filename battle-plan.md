Notes:
~~Helper functions for pre-processing~~
~~Word2Vec Vectorization Success twitter 50dim~~
    ~~Compare vocab to intent~~
~~Tokenize w/ keras(proably not worth the time)~~ 
Clustering with vectorized vocab (issues with nltk Kmeans, doesn't like my dtype)
~~Seq2Seq (char by char) Success! - played with argmax/prob (try other Temps)~~
    
Battle Plan
1. finish trying clustering on intent vocab (nltk/sklearn)
    -Based on result: 
        1. Apply classification method on 10ish classes
        2. Move on to improve seq2seq results
            -Try N-gram or word-based.
            -What does N-gram or word-based look like for code?
