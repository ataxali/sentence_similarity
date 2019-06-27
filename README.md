# Measuring Pairwise Sentence Similarities
Aman Taxali 

ataxali@umich.edu



### Motivation
Recent applications of deep learning methods to language modelling tasks have spawned a variety of context-free and contextual natural language representation models. Context-free embeddings map each word or phrase in the vocabulary to a single real vector in the continuous semantic space. A limitation of this approach is that each element of the vocabulary only has a single vector representation, even if it may have multiple meanings (for example: the word ‘lead’ in phrases ‘lead astray’ and ‘lead pipe’). Contextual embeddings attempt to resolve this issue by incorporating information from neighboring words into each word’s vector representation. The objective of contextual embeddings is to produce representation spaces for sequences of words (like sentences and paragraphs) that generalize well across NLP tasks. 

The aim of this report is to investigate the performance of context-free and contextual embeddings in measuring the semantic similarity of sentence pairs. There are four questions we explore:

•	How well can context-free and context-aware embeddings identify relatedness in sentence pairs? (section 4)

•	How do NLP pre-processing techniques (such as removing stopwords, lemmatization, stemming) effect the performance of context-free and context-aware embeddings? (section 5)

•	Can the performance of context-free models be improved by incorporating information about part-of-speech? (section 6)

•	Do dimension reduction techniques (like PCA and TSNE) qualitatively capture the similarities between sentences? Do unsupervised clustering methods reveal meaning groups of sentences (section 7)?

