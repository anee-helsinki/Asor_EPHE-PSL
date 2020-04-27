## Word vectors used

wordvecs.vec was created with fastText and contains the vectors in text format.

wordvecs.bin was created from the .vec file using convertvec (https://github.com/marekrei/convertvec) because the binary file produced by fastText is not compatible with WordVectors R package used to produce scatter plots (see Visualisation/ folder).
