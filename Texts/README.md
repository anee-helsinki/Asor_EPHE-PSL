### Texts analyzed

The preprocessing of the data has been explained in Tero Alstola, Shana Zaia, Aleksi Sahala, Heidi Jauhiainen, Saana Svärd, & Krister Lindén. (2019). Aššur and His Friends: A Statistical Analysis of Neo-Assyrian Texts. Journal of Cuneiform Studies 71, 159–180. https://doi.org/10.1086/703859.

The Oracc data we use can be found in the Zenodo repository of the previously mentioned article (Texts/Oracc_data) http://doi.org/10.5281/zenodo.2620131.

*textToAnalyse.txt* is the dataset used as input to fastText with each document listed in texts_used on its own line. The lemmas (dictionary forms) as indicated in the Oracc metadata of verbs, nouns, and adjectives are used. Rest of the words are replaced with a underline character '_'.

*igidu_textToAnalyse.txt* is the same dataset as textToAnalyse.txt but with all the words where the transliteration is (in our Oracc data) (d)igi.du replaced with IGI.DU instead of using the lemma indicated in the metadata.

*texts_used* is a list of the 5056 documents in the dataset.
