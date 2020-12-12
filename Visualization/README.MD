## Visualization of the results
#### Most of these illustrations are in the article. The number after the explanation gives the number of the figure.

*CubeWithVectors.pdf* is an illustration of a three-dimensional vector space with three arrows, the tips of which represent the vectors (Figure 1).

*Gods.gephi* is the gephi project from which the network illustrations have been printed. It contains (1) the full graph of all gods (with at least 5 attestations) in the dataset and their connections to each other as indicated by the fastText results (see Lists/mostSimilarWords_gods_FT), (2) the giant component, i.e. the largest connected group, of gods (see Gods_gephi_color.pdf), and (3) the ego network of Nergal (see NergalEgonetwork.pdf).

*Gods_gephi_color.pdf* is a graph produced with Gephi containing the giant component, i.e. the largest group of the gods (with at least 5 attestations in the dataset) that are all connected to each other.

*NergalEgonetwork.pdf* is Nergal's ego network, i.e. a graph with only Nergal and the gods connected to him. (Figure 4)

*NergalIgiduScatterPlot.pdf* is a scatterPlot created with R Studio using Word Vectors R package that can read word vectors build with word2vec. The vectors were produced with fastText and the file analysis_igidu.vec (see the folder WordVectors) was converted to word2vec-compatible binary file with convertvec (https://github.com/marekrei/convertvec) before loading the vectors to R Studio. (Figure 5)

*QueryResultsFastText.pdf* is an example of 15 most similar words when querying fastText for the word for Nergal. (Figure 2)

*VectorCalculus.pdf* is an illustration of finding analogies with fastText using Akkadian words as examples. (Figure 3)
