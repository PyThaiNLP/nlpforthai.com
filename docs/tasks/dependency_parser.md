# Dependency Parser
## Corpus

| Name                          | Description                                                  | Size                               | License      | Creator                                                      | Download                                                     |
| ----------------------------- | ------------------------------------------------------------ | ---------------------------------- | ------------ | ------------------------------------------------------------ | ------------------------------------------------------------ |
| UD Thai PUD                   | This is a part of the Parallel Universal Dependencies (PUD) treebanks created for the CoNLL 2017 shared task on Multilingual Parsing from Raw Text to Universal Dependencies. | 1,000 sentences                    | CC BY-SA 3.0 | Universal Dependencies                                       | [GitHub](https://github.com/UniversalDependencies/UD_Thai-PUD) |
| Blackboard Treebank           | Blackboard Treebank is a Thai dependency corpus based on the LST20 Annotation Guideline. It features dependency structures, constituency structures, word boundaries, named entities, clause boundaries, and sentence boundaries. | 122,851 clauses (38,558 sentences) | CC BY 3.0    | Prachya Boonkwan, NECTEC                                     | [bitbucket](https://bitbucket.org/kaamanita/blackboard-treebank/) or [GitHub](https://github.com/KoichiYasuoka/spaCy-Thai/blob/master/UD_Thai-Corpora/th_blackboard.conllu) |
| Thai Discourse Treebank                   | The Thai Discourse Treebank (TDTB) is a project at Chulalongkorn University, Bangkok, Thailand. The annotation adopts the sense inventory from PDTB 3.0. | 180 documents                    | - | Chulalongkorn University                                       | [GitHub](https://github.com/nlp-chula/thai-discourse-treebank/tree/main/data/th-tdtb) |


## Software

| Name                                                | Description                          | Status | Language   | License                    |
| --------------------------------------------------- | ------------------------------------ | ------ | ---------- | -------------------------- |
| [spaCy-Thai](https://github.com/KoichiYasuoka/spaCy-Thai) | Tokenizer, POS-tagger, and dependency-parser for Thai language, working on Universal Dependencies.              | active | Python 3.X | MIT license         |
| [esupar](https://github.com/KoichiYasuoka/esupar) | Tokenizer, POS-tagger, and dependency-parser with Transformers and SuPar.              | active | Python 3.X | MIT license         |
| [TowerParse](https://github.com/codogogo/towerparse) | TowerParse is a Python tool for multilingual dependency parsing, built on top of the HuggingFace Transformers library. Unlike other multilingual dependency parsers (e.g., UDify , UDapter), TowerParse offers a language-dedicated parsing model for each language (actually, for each test UD treebank, i.e., for languages with multiple treebanks, we offer multiple parsing models).              | ? | Python 3.X | CC0-1.0 license         |
