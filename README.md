# Summary

UD_Greek-Griko is the first Universal Dependencies treebank for Griko, an endangered Greek variety traditionally spoken in central Salento, in the southern part of the Apulia (Puglia) region of Italy.

The initial version comprises 100 sentences drawn from written sources dating from the late 19th to the late 20th century. Future releases will incorporate additional historical texts and contemporary spoken data, expanding the treebank's geographical, chronological, and linguistic coverage.


# Introduction

## About Griko

Griko is a Greek variety traditionally spoken in seven towns in the Salento peninsula of southeastern Italy: Calimera, Castrignano de' Greci, Corigliano d'Otranto, Martano, Martignano, Sternatia, and Zollino. These towns belong to the Union of Municipalities of Grecìa Salentina (*Unione dei Comuni della Grecìa Salentina*).

Griko is primarily an oral variety whose intergenerational transmission began to decline significantly during the second half of the 20th century. This decline has resulted in a progressive reduction in the number of speakers. Today, Griko is considered severely endangered, with its remaining speakers predominantly belonging to older generations and forming small, geographically scattered communities across the seven towns.

The presence of Greek in Salento is attested from the Middle Ages, although the precise historical origins of Griko remain a matter of scholarly debate. One of its defining characteristics is its centuries-long contact with Salentino, the local Italo-Romance variety, and, more recently, with Standard Italian. Sustained language contact and widespread bilingualism have resulted in extensive mutual influence between Griko and the surrounding Italo-Romance varieties, affecting multiple levels of linguistic structure. Consequently, Griko has followed a distinctive developmental trajectory that sets it apart from mainland Greek varieties.

## About the treebank

The initial version of UD_Greek-Griko consists of **100 manually annotated sentences**, constituting the treebank's test set. These sentences correspond to the first 20 sentences of each of five narrative texts representing the Griko varieties of Martano, Calimera, and Sternatia. The texts originate from written sources dating from the late 19th to the late 20th century.

The treebank will be progressively expanded to include additional written materials, particularly traditional narratives and folk poetry, as well as contemporary spoken data collected through spontaneous speech recordings and semi-structured interviews conducted between 2022 and 2026. These additions aim to provide broader coverage of Griko's geographical (diatopic), historical (diachronic), and spoken–written variation, contributing to a more comprehensive representation of the variety within the Universal Dependencies framework.

### Orthographic variation and lemmatization

Griko lacks a standardized orthography, and different written sources employ distinct spelling conventions. Accordingly, **lemmatization generally follows the orthographic conventions of the individual sources**, rather than imposing a uniform spelling system across the treebank. This approach preserves source-specific orthographic variation and reflects the diversity of written representations of Griko.

An exception concerns the auxiliary verb *HAVE*, for which the lemma `echo` has been adopted consistently throughout the treebank, instead of alternative spellings such as `ekho` or `eho`.

## Data sources

- Morosi, G. (1870). *Studi sui dialetti greci della Terra d'Otranto*. Lecce: Editrice Salentina.
- Stomeo, P. (1980). *Racconti greci inediti di Sternatia*. Lecce: La Nuova Ellade.
- Tommasi, S. (1998). *Io' mia forà… Fiabe e racconti della Grecìa Salentina. Dai quaderni (1883–1912) di Vito Domenico Palumbo*. Galatina, Lecce: Ghetonìa.

# Acknowledgments

The development of this treebank was carried out within the framework of **MICRODIACHRO (Microdiachrony in Endangered Languages across Modalities)**, a research project funded by the Spanish Ministry of Science, Innovation and Universities / State Research Agency (grant PID2020-119041GB-I00, 2021–2025).

The Griko component of the project was led by **Josep Quer** (ICREA / Universitat Pompeu Fabra, Barcelona) and **Marika Lekakou** (University of Ioannina).

The development of the treebank has benefited from the collaboration of **Stavros Bompolas** (Institute for Language and Speech Processing & Archimedes Research Unit, Athena Research Center) and **Stella Markantonatou** (Institute for Language and Speech Processing & Archimedes Research Unit, Athena Research Center), who contributed to the preparation and development of the resource within the Universal Dependencies framework.

The linguistic data were annotated by **Emanuela Pinna**, a PhD candidate in the Group of Formal Linguistics (GLiF) at Universitat Pompeu Fabra. Her doctoral research focuses on Griko syntax from a diachronic perspective and is supported by an FI–Joan Oró fellowship awarded by AGAUR (Agency for the Management of University and Research Grants).

## References

Bompolas, S., Pinna, E., Quer, J., Lekakou, M., & Markantonatou, S. (2026). [Structural Divergence under Shared Language-Level Specification: Griko in Universal Dependencies](https://aclanthology.org/2026.dialres-1.31/). In *Proceedings of the First Workshop on Dialects in NLP — A Resource Perspective (DialRes 2026)* (pp. 315–326). Palma de Mallorca, Spain: Association for Computational Linguistics. https://doi.org/10.63317/3qewtwwnj3cx


# Changelog

* 2026-10-29 v2.19
  * Added the test set comprising 100 annotated sentences.
* 2025-05-15 v2.16
  * Initial release in Universal Dependencies.

<pre>
=== Machine-readable metadata (DO NOT REMOVE!) ================================
Data available since: UD v2.18
License: CC BY-SA 4.0
Includes text: yes
Parallel: no
Genre: fiction
Lemmas: manual native
UPOS: manual native
XPOS: not available
Features: manual native
Relations: manual native
Contributors: Markantonatou, Stella; Pinna, Emanuela; Bompolas, Stavros; Lekakou, Maria; Quer, Josep
Contributing: here
Contact: stiliani.markantonatou@gmail.com
===============================================================================
</pre>
