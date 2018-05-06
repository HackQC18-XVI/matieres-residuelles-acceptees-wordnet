# Matières Résiduelles Acceptées + Wordnet

Semantically annotated and augmented version of Ville de Laval's [Matières résiduelles acceptées par collecte](https://www.donneesquebec.ca/recherche/fr/dataset/matieres-residuelles-acceptees-par-collecte) dataset.

This dataset can be used for mapping the various categories with real-world entities, using the [WordNet](https://wordnet.princeton.edu/) lexical database.

The following changes have been made to the original dataset:

* Added a synset ID for each entry, to map it with a lexical entry.
* Added an "id" field for each entry, to improve machine-readability.
* Added "collecte-type" for each entry, to improve machine-readability.
* Split some multi-purpose entries into multiple atomic ones.
* Normalized empty "instructions-speciales" to be `null`.
* Removed empty entry at the end.
* Removed some duplicates or unmappable entries (should be re-introduced!).
