# Multy-word-Expressions-in-Bert
The research is devoted to investigate scpecifity of Multy-word Expressions in Bert.

For work we collect dependency trees from the ru_syntagrus-ud-dev.conllu file of the deep annotated corpus of texts of the Russian language SynTagRus in UD markup. The study examined sentences without ellipsis, foreign words and dates. Based on UD markup, dependency trees were converted into a linear format, into bracket notation, and in its shortened type, since the study considered non-single-word constructions.

For bracket notation, we took into account not words, but their indices. Further work was carried out on the transformation of the bracket notation, which consisted in checking for the presence of a numbering break in order to detect non-projective and weakly projective cases.

Further, from the remaining projective cases, the indices belonging to punctuation marks were removed and renumbered so that the indices corresponded to the words in a sentence in order.

The results of the study showed that the distribution of cosine proximity of words within the components is not similar to the distribution of the same indicators for words at the boundaries of syntactic groups. The assumption about the influence of the type of border on the distribution of values was not confirmed. In particular, the results for more "dense" boundaries turned out to be similar to the results for less "dense" boundaries.
