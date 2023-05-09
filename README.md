# SVMorph
Spanish verb morphology dataset

The dataset includes over 1000 verb types with their morphological inflection and irregularity classification. 
We include all the verbs produced by any speaker in the Spanish portion of the CHILDES data set (MacWhinney, 2000). Each verb is listed
with its stem and all possible tokens, inflected form, English meaning translation, irregularity class for irregular verbs, and
inflection for each person, number, and tense combination.
The irregular verb classification corresponds to the notation used in the Spanish conjugation tables provided by Wiktionary (https://en.wiktionary.org/wiki/Appendix:Spanish_verbs).
A native-speaker of Spanish marked each irregular modification as affecting pronunciation vs. only orthography. T
he context for each verb is provided along with the morphological notation used in the CHILDES and SIG-MORPHON datasets (https://childes.talkbank.org/ and https://github.com/sigmorphon/conll2017).
For completeness, we add frequency data for each verb-context combination from the Spanish portion of CHILDES.

### File structure

The data set is provided in two file types (text and csv). Both files are in UTF-8 encoding. 

| Field  | Meaning |
| ------------- | ------------- |
| SIGstem | The stem of the verb as listed in SIG-MORPHON  |
| SIGprop  | The dimensions of meaning based on the unimorph schema (https://unimorph.github.io/schema)  |
| CHILDESprop | The dimensions of meaning based on the CHILDES schema (https://talkbank.org/manuals/MOR.pdf) |
| SIGverb | The gloss of the verb corresponding to the verb stem and meaning |
| VerbType | The verb type (ar, er, or ir) |
| English | The English translation of the Spanish stem |
| StemFrequency| The type frequency of the verb in CHILDES |
| Person | Person (1, 2, or 3) |
| Tense | Tense (Condtional, Future, Present, SUBJ_PRESENT, Imperfect, Preterit, or SUBJ_IMP) |
| Number | Number (S for singular, or P for plural) |
| RegularInflection | The regular inflection expected for the dimensions of meaning |
| RuleType | Irregularity class for irregular verbs |
| Regularity | Regular or Irregular marking for the gloss |
| Rule1 | First modification for the irregular gloss |
| Rule2 | Second modification for the irregular gloss |

### How to cite

Barak, L., Fernandez, N., Feldman, N. H. & Shafto, P. (2023). Modeling Substitution Errors in Spanish Morphology Learning. In Proceedings of the Annual Meeting of the Cognitive Science Society (Vol. 45, No. 45).

@inproceedings{barak2023modeling,
  title={Modeling Substitution Errors in Spanish Morphology Learning.},
  author={Barak, Libby and Fernandez, Nathalie and Feldman, Naomi H and Shafto, Patrick},
  booktitle={Proceedings of the Annual Meeting of the Cognitive Science Society},
  year={2023}
}

### Link to the paper

The data for the simulations can be found under CogSci23

