## Visualization of the results
# Some of the illustrations are used in the article. The number after the explanation gives the number of the figure.

*CubeWithVectors.pdf* is an illustration of a three-dimensional vector space with three arrows, the tips of which represent the vectors (Figure 1).

*Gods.gephi* is the gephi project from which the illustration have been printed. It contains (1) the full graph of all gods (with at least 5 attestations) in the dataset and their connections to each other as indicated by the fastText results (see Lists/mostSimilarWords_gods_FT), (2) the giant component, i.e. the largest connected group, of gods (see Gods_gephi_color.pdf), and (3) the ego network of Nergal (see NergalEgonetwork.pdf).

*Gods_gephi_color.pdf* is a graph produced with Gephi containing the largest group of the gods (with at least 5 attestations in the dataset) that are all connected to each other.

*NergalEgonetwork.pdf* is a graph with only Nergal and the gods connected to him. (Figure 4)

*NergalIgiduScatterPlot.pdf* is a scatterPlot created with R Studio using Word Vectors R package that can read word vectors build with word2vec. The vectors were produced with fastText and the analysis_igidu.vec (see WordVectors/) was converted to w2v-compatible binary file with convertvec (https://github.com/marekrei/convertvec). (Figure 5)

*QueryResultsFastText.pdf* is an example of 15 most similar words when one queries fastText for the word for Nergal. (Figure 2)

*VectorCalculus.pdf* is an illustration of finding analogies with fastText using Akkadian words as examples. (Figure 3)
