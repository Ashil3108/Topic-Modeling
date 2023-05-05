# Topic-Modeling
Identified Potential Topics across different document as well as with the document.

### Data Set:NIPS Papers
Neural Information Processing Systems (NIPS) is one of the top machine learning conferences in the world. <br>
It covers topics ranging from deep learning and computer vision to cognitive science and reinforcement learning.<br>
This dataset includes the title, authors, abstracts, and extracted text for all NIPS papers to date (ranging from the first 1987 conference to the current 2016 conference). <br>
Source: https://www.kaggle.com/datasets/benhamner/nips-papers

### Data-Preprocessing
Tokenization: the process of segmenting text into words, clauses, or sentences (here we will separate words and remove punctuation) <br>
Removal stop words : removal of commonly used words unlikely to be useful for learning, such as “the”, “if”, “and”... <br>
Lemmatization: The goal of lemmatization is to reduce inflectional forms and sometimes derivationally related forms of a word to a common base form  (e.g. gives -> give)
Lower-case Conversion: converting all texts in to lower case.

### Training Topic Models
LDA(Latent Dirichlet Allocation): It is a generative probabilistic model of a corpus.The basic idea is that documents are represented as random mixtures over latent topics, where each topic is characterized by a distribution over words. <br>
LSI(Latent Semantic Indexing): It comes from the need to discover relevant documents from search words.The main idea behind LSI is to utilize term co-occurrence to derive a set of latent concepts, words which frequently occur together are assumed to be more semantically associated.
 







