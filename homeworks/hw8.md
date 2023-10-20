One critical hyperparameter in the [word2vec](https://arxiv.org/pdf/1301.3781.pdf) model is the size of the context window i.e. how many tokens on the left or right of some word should be considered to say that words cooccur. Let's suppose we learn two word2vec models, A and B, which are the similar in all the settings except the size of the context window. For model A, let's suppose that the size of the context window is 1 and for model B, let's suppose that the size of the context window is 100 (or a large value comparable to the average size of a document). Answer the following questions:

a) Which model will take more time to learn the embeddings assuming they are both trained on the same corpus?
b) Which model will learn embeddings such that the embedding of any word (e.g., run) will be closer to the embedding of syntactically similar words (e.g., running) on average?

You don't have to run any model to answer these questions.

Best,
Sandeep
