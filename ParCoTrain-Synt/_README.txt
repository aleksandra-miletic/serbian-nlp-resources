### ParCoTrain-Synt, v1.0 ###


This archive contains a gold corpus for the POS-tagging, detailed morphosyntactic annotation, lemmatisation and dependency parsing of Serbian. The corpus contains 101K tokens annotated manually on all levels. The source texts for the corpus are contemporary Serbian novels from the 2nd half of the 20th century.

### FORMAT

The corpus is presented in the standard CONLL-X format. It is a column-based format in which the sentences are verticalized, with each line containing the annotation of one token. The lines are structured as follows:

[ID]\t[TOKEN]\t[LEMMA]\t[POS]\t[FULL MORPHOSYNTACTIC TAG]\t[MORPHOSYNTACTIC TRAITS]\t[HEAD ID]\t[SYNTACTIC FUNCTION]\t[HEAD ID]\t[SYNTACTIC FUNCTION]\n

NB: In case of a non-projective syntactic relation, the last two columns should contain the ID of the artificial projective head of the token and the corresponding projective relation. However, in this first release of the corpus, they contain the same information as columns 7 and 8.

The sentences are separated by blank lines.

A detailed description of the morphosyntactic and syntactic annotation layers is available in the associated annotation guidelines, distributed with the corpus (in French). A documentation in English and Serbian will soon be made available.

### CORPUS SPLIT

The corpus is split into three sections:

file					size (tokens)		purpose
parcotrain-synt_train_v1.0.conll	80 869			training 
parcotrain-synt_dev_v1.0.conll		9 998			fine-tuning
parcotrain-synt_test_v1.0.conll		10 162			evaluation
parcotrain-synt_full_v1.0.conll		101 029			full corpus

### LICENCE
Some rights are reserved. ParCoTrain-Synt is distributed under a Creative Commons BY-NC-SA 3.0 licence. Please read the licence carefully before using the corpus in your work. 

### REFERENCING THE CORPUS

When using the corpus, please cite the following work:

Miletic, Aleksandra (2018). Un treebank pour le serbe : constitution et exploitations. Thèse de doctorat. Université de Toulouse - Jean Jaurès, France. 

The thesis contains a detailed account of the corpus building process, as well as some experiments in parsing and linguistics based on it. Some of the experiments were done on an initial 81K token sample. This sample, with its original split into train, test and dev sections, is also provided (folder ParCoTrain-Synt-v0.1).


### CONTACT
Aleksandra Miletic: aleksandra.miletic [at] univ-tlse2.fr


