## Word vectors used

The following word vectors were created from the file /Texts/textToAnalyse.txt.

*analysis.bin* was created with fastText and contains the vectors in binary format.

*analysis.vec* was created with fastText and contains the vectors in text format.

The following word vectors were created from the file /Texts/igidu_textToAnalyse.txt. All the words transliterated as (d)igi.du are replaced with the lemma IGI.DU instead of using the original lemma in the Oracc metadata.

*analysis_igidu.vec* contains the vectors in text format.

*vectorsConverted.bin* was created from the analysis_igidu.vec file using convertvec (https://github.com/marekrei/convertvec), because the binary file produced by fastText is not compatible with the WordVectors R package (https://github.com/bmschmidt/wordVectors) used to produce scatter plots (see the folder Visualization).
