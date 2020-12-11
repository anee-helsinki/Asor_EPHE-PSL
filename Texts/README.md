### Texts analyzed

The preprocessing of the data has been explained in Tero Alstola, Shana Zaia, Aleksi Sahala, Heidi Jauhiainen, Saana Svärd, & Krister Lindén. (2019). Aššur and His Friends: A Statistical Analysis of Neo-Assyrian Texts. Journal of Cuneiform Studies 71, 159–180. https://doi.org/10.1086/703859.

The Oracc data we use can be found in the Zenodo repository of the above-mentioned article (Texts/Oracc_data) http://doi.org/10.5281/zenodo.2620131.

*textToAnalyse.txt* is the dataset used as input to fastText with each document on its own line. The documents used are listed in *texts_used*. The lemmas (dictionary forms) of verbs, nouns, and adjectives are used as indicated in the Oracc metadata. Rest of the words are replaced with an underline character '_'.

*igidu_textToAnalyse.txt* is the same dataset as textToAnalyse.txt, but all the words transliterated as (d)igi.du are replaced with the lemma IGI.DU instead of using the original lemma in the Oracc metadata.

*texts_used* is a list of the 5,056 documents in the dataset.
