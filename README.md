# serbian-nlp-resources
## Parsing, tagging and lemmatisation resources for Serbian

This repository contains the NLP resources for Serbian developed as part of the following work:

Miletic, Aleksandra (2018). Un treebank pour le serbe : constitution et exploitations. Thèse de doctorat. Université de Toulouse - Jean Jaurès, France.

These resources include:

- **ParCoTrain-Synt**: a 101K token treebank, manually annotated with POS tags, detailed morphosyntactic tags, atomic morphosyntactic traits, lemmas, and syntactic dependencies. 

- **ParCoLex**: a morphosyntactic lexicon with 6M entries.

- **Transition-based parsing model**: a parsing model created using the Talismane parser.

- **Graph-based parsing model**: a parsing model created using the MST parser.

- **Morphosyntactic-tagging model**: a POS tagging model using detailed morphosyntactic tags developed with the HunPOS tagger.

- **Lemmatization model**: a lemmatization model developed with the CSTLemma lemmatizer.

The parsing and tagging models were trained on the **ParCoTrain-Synt** corpus, whereas the lemmatization model was trained on a training lexicon adapted from the **ParCoLex** lexicon.

The corpus and the models trained on it are distributed under the [Creative Commons BY-NC-SA 3.0 license](https://creativecommons.org/licenses/by-nc-sa/3.0/).
The lexicon and the lemmatization model are distributed under the [Creative Commons BY-SA 4.0 license](https://creativecommons.org/licenses/by-sa/4.0/).
