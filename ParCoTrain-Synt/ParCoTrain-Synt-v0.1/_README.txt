### ParCoTrain-Synt-v0.1 ###

This archive contains a training and test corpus for the POS-tagging, detailed morphosyntactic annotation, lemmatisation and parsing of Serbian. The corpus contains 81K tokens annotated manually on all levels. The source texts for the corpus are contemporary Serbian novels from the 2nd half of the 20th century.

# FORMAT
The corpus is presented in the standard CONLL-X format. It is a column-based format in which the sentences are verticalized, with each line containing the annotation of one token. The lines are structured as follows:

[ID]\t[TOKEN]\t[LEMMA]\t[POS]\t[FULL MSD]\t[MORPHOSYNT. TRAITS]\t[HEAD ID]\t[SYNT. FUNCTION]\t[HEAD ID]\t[SYNT. FUNCTION]\n

NB: In case of a non-projective syntactic relation, the last two columns should contain the ID of the artificial projective head of the token and the corresponding projective relation. However, in this first release of the corpus, they contain the same information as columns 7 and 8.

The sentences are separated by blank lines.

A detailed description of the morphosyntactic and syntactic annotation layers will soon be available.

# CORPUS SPLIT

The corpus is split into three sections:

file								size (tokens)	purpose
80k-parcolab-syntax-train-v2.conll	69350			training 
80k-parcolab-syntax-test-v2.conll	7803			evaluation
80k-parcolab-syntax-dev-v2.conll	4051			development (fine-tuning of the parsing parameters)

# LICENCE
Some rights are reserved. ParCoTrain-Synt is distributed under a Creative Commons BY-NC-SA 3.0 licence. Please read the licence carefully before using the corpus in your work.

# AUTHORS
This resource was developed by Aleksandra Miletic, Dejan Stosic and Cécile Fabre (CLLE, CNRS & University of Toulouse).

# CONTACT
Aleksandra Miletic: aleksandra.miletic [at] univ-tlse2.fr
