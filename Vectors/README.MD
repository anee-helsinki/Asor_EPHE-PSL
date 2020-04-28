## Word vectors used

*wordvecs.vec* was created with fastText and contains the vectors in text format.


The "igidu" word vectors were created after we had replaced all the words in the dataset which in Oracc metadata have transliteration {d}igi.du, whether the dictionary form given is Nergal or Palil, with the word IGI.DU:

*wordvecs_igidu.vec* contains the vectors in text format.

*wordvecs_igidu.bin* was created from the .vec file using convertvec (https://github.com/marekrei/convertvec) because the binary file produced by fastText is not compatible with WordVectors R package used to produce scatter plots (see Visualization/ folder).
