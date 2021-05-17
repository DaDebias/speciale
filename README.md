# Towards gender de-biased Danish Word Embeddings: An investigation of bias in current Danish pre-trained word embedding models

This GitHub repository includes all Python code that was used for the analysis that was part of the thesis "Towards gender de-biased Danish Word Embeddings: An investigation of bias in current Danish pre-trained word embedding models
".

The analysis is stored in three code files:
1) "Exploratory analysis" - code for the exploratory analysis. This code makes t-SNE plots for all the six pre-trained word embedding models investigated. This code is described in the section called "Exploratory data analysis with t-SNE"

2) "WEAT" - code for the investigation of bias in the six pre-trained Danish word embeddings models investigated. The code runs the Word Embedding Association TEST (WEAT). This code is described in the "WEAT implementation" section of the thesis.

3) "WEAT replication" - code for the replication of the original English WEAT results by Caliskan et al (2017). This code is described as part of the "WEAT implementation" section of the thesis. The code is used to secure that the WEAT equations are implemented correctly.


Attention: Loading the pre-trained embeddings
As described in the thesis, most of the pre-trained embeddings can be downloaded and loaded directly using daNLP. However, the 'Kongelige Bibliotek' and 'Sketchengine' embedding must be downloaded first and placed in the same folder as the code. Links for download are provided in the thesis.
