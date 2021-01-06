# NLP For Thai

It's Thai NLP homepage. All is Open Source. [Work in process...]

Website: [NLPForThai.com](https://nlpforthai.com) maintained by PyThaiNLP

**Menu**

- [Software](#software)
- [Corpus/Dataset](#corpusdataset)
- [Tools](#tools)
- [Pre-trained models/Models](#pre-trained-modelsmodels)

## Software

**Menu**

[WIP]

### Word Segmentation

| Name                                                         | Description                                                  | Status   | Language            | License                    |
| ------------------------------------------------------------ | ------------------------------------------------------------ | -------- | ------------------- | -------------------------- |
| [ICU](http://site.icu-project.org/home)                      | ICU - International Components for Unicode                   | active   | C/C++/Java          | Unicode License            |
| [libthai](https://github.com/tlwg/libthai)                   | is a set of Thai language support routines aimed to ease developers' tasks to incorporate Thai language support in their applications. | active   | C/C++               | LGPL-2.1 License           |
| [SWATH](https://github.com/tlwg/swath)                       | Smart Word Analysis for THai                                 | active   | C/C++               | GPL-2.0 License            |
| [AttaCut](https://github.com/PyThaiNLP/attacut)              | Fast and Reasonably Accurate Word Tokenizer for Thai.        | active   | Python 3.X          | MIT License                |
| [PyThaiNLP](https://github.com/PyThaiNLP/pythainlp)          | It's part of PyThaiNLP.                                      | active   | Python 3.X          | Apache License 2.0         |
| [PyWordCut](https://github.com/veer66/wordcutpy)             | wordcutpy is a simple Thai word breaker written in Python 3+ | active   | Python 3.X          | LGPLv3                     |
| [DeepCut](https://github.com/rkcosmos/deepcut)               | A Thai word tokenization library using Deep Neural Network.  | active   | Python 3.X          | MIT License                |
| [TLTK](https://pypi.org/project/tltk/)                       | Thai Language Toolkit                                        | active   | Python 3.X          | BSD License (BSD-3-Clause) |
| [KUCut](https://github.com/Thanabhat/KUCut)                  | Thai word segmentor that is difference from existing segmentor such as CTTEX or SWATH. | deactive | Python 2.4-2.5      | GPL-2.0 License            |
| [SEFR CUT](https://github.com/mrpeerat/SEFR_CUT)             | Stacked Ensemble Filter and Refine for Word Segmentation     | active   | Python 3.X          | MIT License                |
| [CutKum](https://github.com/pucktada/cutkum)                 | Thai Word-Segmentation with LSTM in Tensorflow               | -        | Python 3.X          | MIT License                |
| [ThaiLMCut](https://github.com/meanna/ThaiLMCUT)             | Word Tokenizer for Thai Language based on Transfer Learning and bidirectional-LSTM | active   | Python 3.X          | MIT License                |
| [LexTo](http://www.sansarn.com/lexto/)                       | Thai word segmentation ( Longest Matching )                  | -        | Java                | LGPLv2.1                   |
| [sertiscorp /thai-word-segmentation](https://github.com/sertiscorp/thai-word-segmentation) | Thai word segmentation with bi-directional RNN               | -        | Python 3.X          | MIT License                |
| [Thai Analysis Plugin for Elasticsearch](https://github.com/tlefsad/elasticsearch-analysis-thaichub2) | The Thaichub2 (thai-chub-chub) Analysis Plugin integrates the Thai word segmentation modules into Elasticsearch. | active   | Java                | Apache-2.0 License         |
| [Wordcut](https://github.com/veer66/wordcut)                 | Thai word breaker for Node.js                                | active   | JavaScript, Node.JS | LGPLv3                     |
| [newmm-tokenizer](https://github.com/wisesight/newmm-tokenizer) | Standalone Dictionary-based, Maximum Matching + Thai Character Cluster (newmm) tokenizer extracted from PyThaiNLP. | active   | Python 3.X          | Apache License 2.0         |
| [Stanza](https://github.com/stanfordnlp/stanza)              | Official Stanford NLP Python Library for Many Human Languages | active   | Python 3.X          | Apache License 2.0         |
| [Multi Candidate Thai Word Segmentation](https://github.com/earthy123/Multi-Candidate-Word-Segmentation) | Most existing word segmentation methods output one single segmentation solution. | active   | Python 3.X          | MIT License                |
| [PhlongTaIam](https://github.com/veer66/PhlongTaIam)         | PHP Thai word breaker                                        | active   | PHP                 | LGPL-2.1 License           |

### Syllable Segmentation

| Name                                   | Description                     | Status | Language   | License                    |
| -------------------------------------- | ------------------------------- | ------ | ---------- | -------------------------- |
| [ssg](https://github.com/ponrawee/ssg) | CRF syllable segmenter for Thai | active | Python 3.X | Apache License 2.0         |
| [TLTK](https://pypi.org/project/tltk/) | Thai Language Toolkit           | active | Python 3.X | BSD License (BSD-3-Clause) |

### Sentence Segmentation

| Name                                                | Description                                              | Status | Language   | License                    |
| --------------------------------------------------- | -------------------------------------------------------- | ------ | ---------- | -------------------------- |
| [PyThaiNLP](https://github.com/PyThaiNLP/pythainlp) | It's part of PyThaiNLP.                                  | active | Python 3.X | Apache License 2.0         |
| [TLTK](https://pypi.org/project/tltk/)              | Thai Language Toolkit                                    | active | Python 3.X | BSD License (BSD-3-Clause) |
| [BoydCut](https://github.com/BigDataRPG/BoydCut)    | Bidirectional LSTM-CNN Model for Thai Sentence Segmenter | active | Python 3.X | MIT License                |

### Part Of Speech

| Name                                                | Description             | Status | Language   | License                    |
| --------------------------------------------------- | ----------------------- | ------ | ---------- | -------------------------- |
| [PyThaiNLP](https://github.com/PyThaiNLP/pythainlp) | It's part of PyThaiNLP. | active | Python 3.X | Apache License 2.0         |
| [TLTK](https://pypi.org/project/tltk/)              | Thai Language Toolkit   | active | Python 3.X | BSD License (BSD-3-Clause) |

### OCR

| Name                                                        | Description                                                  | Status | Language   | License            |
| ----------------------------------------------------------- | ------------------------------------------------------------ | ------ | ---------- | ------------------ |
| [Tesseract OCR](https://github.com/tesseract-ocr/tesseract) | Tesseract Open Source OCR Engine                             | active | C/C++      | Apache License 2.0 |
| [Easy OCR](https://github.com/JaidedAI/EasyOCR)             | Ready-to-use OCR with 40+ languages supported including Chinese, Japanese, Korean and Thai. | active | Python 3.X | Apache License 2.0 |

### Spell Check

| Name                                                | Description                                                  | Status | Language   | License                                                      |
| --------------------------------------------------- | ------------------------------------------------------------ | ------ | ---------- | ------------------------------------------------------------ |
| [Hunspell](http://hunspell.github.io/)              | Hunspell is the spell checker of LibreOffice, OpenOffice.org, Mozilla Firefox 3 & Thunderbird, Google Chrome. | active | C/C++      | GNU Lesser General Public License and Mozilla Public License |
| [PyThaiNLP](https://github.com/PyThaiNLP/pythainlp) | It's part of PyThaiNLP.                                      | active | Python 3.X | Apache License 2.0                                           |

### Dependency parser

| Name                                                      | Description                                                  | Status | Language   | License     |
| --------------------------------------------------------- | ------------------------------------------------------------ | ------ | ---------- | ----------- |
| [spaCy-Thai](https://github.com/KoichiYasuoka/spaCy-Thai) | Tokenizer, POS-tagger, and dependency-parser for Thai language, working on Universal Dependencies. | active | Python 3.X | MIT License |

### Grapheme to Phoneme

| Name                                                         | Description                                                  | Status | Language   | License                    |
| ------------------------------------------------------------ | ------------------------------------------------------------ | ------ | ---------- | -------------------------- |
| [PyThaiNLP](https://github.com/PyThaiNLP/pythainlp)          | It's part of PyThaiNLP.                                      | active | Python 3.X | Apache License 2.0         |
| [TLTK](https://pypi.org/project/tltk/)                       | Thai Language Toolkit                                        | active | Python 3.X | BSD License (BSD-3-Clause) |
| [thpronun](https://github.com/tlwg/thpronun)                 | thpronun is a program for analyzing pronunciation of Thai words. The output can be in Thai pronunciation, Romanization, or in any other phonetic systems. It is designed to be extensible. | active | C/C++      | GPL-3.0 License            |
| [Thai G2P (grapheme to phoneme)](https://github.com/nozomiyamada/thaig2p) | dictionary-based conversion + BiLSTM seq2seq model (under construction) | active | Python 3.X |                            |

### Named Entity Recognition

| Name                                                | Description             | Status | Language   | License                    |
| --------------------------------------------------- | ----------------------- | ------ | ---------- | -------------------------- |
| [PyThaiNLP](https://github.com/PyThaiNLP/pythainlp) | It's part of PyThaiNLP. | active | Python 3.X | Apache License 2.0         |
| [TLTK](https://pypi.org/project/tltk/)              | Thai Language Toolkit   | active | Python 3.X | BSD License (BSD-3-Clause) |

### Soundex

| Name                                                | Description             | Status | Language   | License            |
| --------------------------------------------------- | ----------------------- | ------ | ---------- | ------------------ |
| [PyThaiNLP](https://github.com/PyThaiNLP/pythainlp) | It's part of PyThaiNLP. | active | Python 3.X | Apache License 2.0 |

### Text Generator

| Name                                                    | Description         | Status | Language   | License            |
| ------------------------------------------------------- | ------------------- | ------ | ---------- | ------------------ |
| [TTG](https://github.com/PyThaiNLP/Thai-Text-Generator) | Thai Text Generator | active | Python 3.X | Apache License 2.0 |

## Corpus/Dataset

**Menu**

[WIP]

### Word Segmentation Corpus

| Name                                           | Description                                                  | Size                                                         | License                                    | Creator                                                      | Download                                                     |
| ---------------------------------------------- | ------------------------------------------------------------ | ------------------------------------------------------------ | ------------------------------------------ | ------------------------------------------------------------ | ------------------------------------------------------------ |
| BEST I (BEST 2009)                             | Benchmark for Enhancing the Standard of Thai language processing | 5,000,000 word                                               | CC BY-SA-NC 4.0                            | NECTEC                                                       | [aiforthai](https://aiforthai.in.th/corpus.php) (registration required) and [Mirror from @korakot](https://github.com/korakot/corpus/tree/main/BEST) |
| LST20 Corpus                                   | LST20 is a large-scale corpus with multiple layers of linguistic annotation for Thai language processing. | 3,164,864 words, 288,020 named entities, 248,962 clauses, and 74,180 sentences | ? (Free for research and open source only) | NECTEC                                                       | [aiforthai](https://aiforthai.in.th/corpus.php) (registration required) |
| Wisesight Samples with Word Tokenization Label | This directory contains samples of Thai social media text, tokenized by humans. These samples are randomly drawn from the full Wisesight Sentiment Corpus. | 160 sentences (wisesight-160) and 1,000 sentences (wiseight-1000) | CC0-1.0 License                            | Nitchakarn Chantarapratin, Pattarawat Chormai, Ponrawee Prasertsom, Jitkapat Sawatphol, Nozomi Yamada, and Attapol Rutherford | [GitHub](https://github.com/PyThaiNLP/wisesight-sentiment/tree/master/word-tokenization) |
| Thai National Historical Corpus (TNHC)         | texts from Thai National Historical Corpus, stored by lines (manually tokenized). | 47 documents, 756,478 lines, 13,361,142 characters           |                                            | Jitkapat Sawatphol                                           | [GitHub](https://github.com/jitkapat/thailitcorpus/releases/tag/v.1.0) |
| Orchid Corpus                                  | Thai part of speech (POS) tagged corpus                      | 5,200 sentences                                              | CC BY-SA-NC 4.0                            | NECTEC                                                       | [Mirror from @wannaphong](https://github.com/wannaphong/corpus_mirror/releases/tag/orchid-v1.0) |

### Part of Speech

| Name                  | Description                                                  | Size                                                         | License                                    | Creator                | Download                                                     |
| --------------------- | ------------------------------------------------------------ | ------------------------------------------------------------ | ------------------------------------------ | ---------------------- | ------------------------------------------------------------ |
| Orchid Corpus         | Thai part of speech (POS) tagged corpus                      | 5,200 sentences                                              | CC BY-SA-NC 4.0                            | NECTEC                 | [Mirror from @wannaphong](https://github.com/wannaphong/corpus_mirror/releases/tag/orchid-v1.0) |
| LST20 Corpus          | LST20 is a large-scale corpus with multiple layers of linguistic annotation for Thai language processing. | 3,164,864 words, 288,020 named entities, 248,962 clauses, and 74,180 sentences | ? (Free for research and open source only) | NECTEC                 | [aiforthai](https://aiforthai.in.th/corpus.php) (registration required) |
| UD Thai PUD           | This is a part of the Parallel Universal Dependencies (PUD) treebanks created for the CoNLL 2017 shared task on Multilingual Parsing from Raw Text to Universal Dependencies. | 1,000 sentences                                              | CC BY-SA 3.0                               | Universal Dependencies | [GitHub](https://github.com/UniversalDependencies/UD_Thai-PUD) |
| thai-political-tweets | A small Thai political twitter dataset with UD POS tags      | 41 tweets, 965 words                                         | Unlicense License                          | Can Udomcharoenchaikit | [GitHub](https://github.com/c4n/thai-political-tweets)       |

### Treebank

| Name        | Description                                                  | Size            | License      | Creator                                                      | Download                                                     |
| ----------- | ------------------------------------------------------------ | --------------- | ------------ | ------------------------------------------------------------ | ------------------------------------------------------------ |
| UD Thai PUD | This is a part of the Parallel Universal Dependencies (PUD) treebanks created for the CoNLL 2017 shared task on Multilingual Parsing from Raw Text to Universal Dependencies. | 1,000 sentences | CC BY-SA 3.0 | Universal Dependencies                                       | [GitHub](https://github.com/UniversalDependencies/UD_Thai-PUD) |
| thtb        | To enable research oppotunities with very few Thai Computational Linguitic resources, we willingly introduce fundamental high-level language resouces built with passion, Thai Treebanks, build from scratch for researchers and enthusiasts. | 5,200 sentences | CC BY 4.0    | Pechlada Seenual, Thodsaporn Chay-intr and Thanaruk Theeramunkong | [GitHub](https://github.com/tchayintr/thtb)                  |

### Natural Language Inference

| Name | Description                                                  | Size                           | License      | Creator           | Download                                           |
| ---- | ------------------------------------------------------------ | ------------------------------ | ------------ | ----------------- | -------------------------------------------------- |
| XNLI | The Cross-lingual Natural Language Inference (XNLI) corpus is a crowd-sourced collection of 5,000 test and 2,500 dev pairs for the MultiNLI corpus. The pairs are annotated with textual entailment and translated into 14 languages: French, Spanish, German, Greek, Bulgarian, Russian, Turkish, Arabic, Vietnamese, Thai, Chinese, Hindi, Swahili and Urdu. | 5,000 test and 2,500 dev pairs | CC BY-NC 4.0 | Facebook Research | [GitHub](https://github.com/facebookresearch/XNLI) |

### Parallel Corpus

| Name                                                    | Description                                                  | Size                                               | License         | Creator                                                      | Download                                                     |
| ------------------------------------------------------- | ------------------------------------------------------------ | -------------------------------------------------- | --------------- | ------------------------------------------------------------ | ------------------------------------------------------------ |
| TALPCo                                                  | TUFS Asian Language Parallel Corpus                          | 1,327 sent                                         | CC BY 4.0       | Nomoto, Hiroki, Kenji Okano, Sunisa Wittayapanyanon and Junta Nomura | [GitHub](https://github.com/matbahasa/TALPCo)                |
| scb-mt-en-th-2020                                       | English-Thai Machine Translation Dataset with the collaboration between Vidyasirimedhi Institute of Science and Technology (VISTEC) and Digital Economy Promotion Agency (depa), publishes an open English-Thai machine translation dataset, with the sponsorship from Siam Commercial Bank (SCB) | 1,001,752 segment pairs                            | CC BY-SA 4.0    | AI Research Institute of Thailand (AIResearch)               | [GitHub](https://github.com/vistec-AI/dataset-releases/releases/tag/scb-mt-en-th-2020_v1.0) |
| Software Documentation Data Set for Machine Translation | A parallel evaluation data set of SAP software documentation with document structure annotation | dev: 2048  segment pairs, test: 2050 segment pairs | CC BY-NC 4.0    | SAP                                                          | [GitHub](https://github.com/SAP/software-documentation-data-set-for-machine-translation) |
| Thai Lao Parallel corpus                                | Thai Lao Parallel corpus                                     |                                                    | CC0-1.0 License | Wannaphong Phatthiyaphaibun                                  | [GitHub](https://github.com/PyThaiNLP/Thai-Lao-Parallel-Corpus) |

### Text Classification

| Name                            | Description                                                  | Size                                         | Labels    | License          | Creator                                                      | Download                                                     |
| ------------------------------- | ------------------------------------------------------------ | -------------------------------------------- | --------- | ---------------- | ------------------------------------------------------------ | ------------------------------------------------------------ |
| prachathai-67k                  | News Article Corpus from Prachathai.com                      | 67,889 articles wtih 51,797 tags             | 12        | CC BY 4.0        | @lukkiddd and @cstorm125                                     | [GitHub](https://github.com/PyThaiNLP/prachathai-67k)        |
| wisesight sentiment             | Social media messages in Thai language with sentiment label (positive, neutral, negative, question). | 26,737 messages                              | 4         | CC0-1.0 License  | Arthit Suriyawongkul,  Ekapol Chuangsuwanich                 | [GitHub](https://github.com/PyThaiNLP/wisesight-sentiment)   |
| wongnai corpus                  | This project is a collection of Wongnai's datasets which are mostly in Thai language. | 500K words labeled                           | 5         | LGPL-3.0 License | wongnai                                                      | [GitHub](https://github.com/wongnai/wongnai-corpus)          |
| Toxicity in Thai Tweet Corpus   | Toxicity in Thai Tweet Corpus                                | 3,300 messages                               | 2         | CC BY-NC 4.0     | Tokyo Metropolitan University Natural Language Processing Group | [GitHub](https://github.com/tmu-nlp/ThaiToxicityTweetCorpus) |
| Thai-Clickbait                  | The dataset for Thai Clickbait classification                | train: 37,376 messages, test: 9,344 messages | 1         | MIT License      | @9meo at GitHub                                              | [GitHub](https://github.com/9meo/Thai-Clickbait)             |
| sentiment_analysis_thai         | Thai sentiment analysis from @JagerV3                        |                                              | 2         | ?                | @JagerV3 at GitHub                                           | [GitHub](https://github.com/JagerV3/sentiment_analysis_thai) |
| thai-emojification              | Emojification of Thai Text, Using Deep Learning (LSTM).      | train: 128 messages, test: 55 messages       | 5 (❤️😄😞🍴⚾) | GPL-3.0 License  | iApp Technology Co, Ltd                                      | [GitHub](https://github.com/kobkrit/thai-emojification)      |
| The 40 Thai Children Stories    | The dataset was collected from 40 Thai children stories. We manually split the text into sentences which leads to 1,964 sentences | 1,964 sentences                              | 3         | ?                | Kitsuchart Pasupa, Thititorn Seneewong Na Ayutthaya          | [GitHub](https://github.com/dsmlr/40-Thai-Children-Stories)  |
| Thai sentiment analysis dataset | Thai sentiment analysis dataset from PyThaiNLP               |                                              | 2         | CC BY 3.0        | PyThaiNLP                                                    | [GitHub](https://github.com/PyThaiNLP/thai-sentiment-analysis-dataset) |

### OCR Dataset

| Name                  | Description                                | Size                       | License         | Creator                 | Download                                                     |
| --------------------- | ------------------------------------------ | -------------------------- | --------------- | ----------------------- | ------------------------------------------------------------ |
| KVIS Thai OCR Dataset | Offline Thai Handwritten Character Dataset |                            | CC BY  4.0      | John Joseph, Ferdin Joe | [Website](https://data.mendeley.com/datasets/8nr3pbdk5c/1)   |
| Thai OCR              | Thai ocr dataset from NECTEC               | Training set: 81,100 image | CC BY-SA-NC 3.0 | NECTEC                  | [aiforthai](https://aiforthai.in.th/corpus.php) (registration required) |

### Text Summarization

| Name    | Description                                      | Size                      | License     | Creator               | Download                                                  |
| ------- | ------------------------------------------------ | ------------------------- | ----------- | --------------------- | --------------------------------------------------------- |
| ThaiSum | The largest dataset for Thai text summarization. | 350,000 articles (2.9 GB) | MIT Licence | Nakhun Chumpolsathien | [GitHub](https://github.com/nakhunchumpolsathien/ThaiSum) |
| TR-TPBS | A dataset for Thai text summarization.           | 310K articles             | MIT License | Nakhun Chumpolsathien | [GitHub](https://github.com/nakhunchumpolsathien/TR-TPBS) |

### Question Answering

| Name    | Description                                                  | Size                                           | License            | Creator         | Download                                                     |
| ------- | ------------------------------------------------------------ | ---------------------------------------------- | ------------------ | --------------- | ------------------------------------------------------------ |
| XQuAD   | XQuAD (Cross-lingual Question Answering Dataset) is a benchmark dataset for evaluating cross-lingual question answering performance. | 240 paragraphs and 1,190 question-answer pairs | CC BY-SA  4.0      | DeepMind        | [GitHub](https://github.com/deepmind/xquad)                  |
| Thai QA | Question answering program from Thai Wikipedia.              | 4,000 question-answer pairs                    | CC BY-SA-NC 3.0    | NECTEC          | Dataset: [aiforthai](https://aiforthai.in.th/corpus.php) (registration required), wiki: [copycatch](http://www.copycatch.in.th/documents-nsc.tar.gz), Sample data set: [copycatch](http://www.copycatch.in.th/qa-output100.json) |
| TyDi QA | A Benchmark for Information-Seeking Question Answering in Typologically Diverse Languages | 200k human-annotated question-answer pairs     | Apache-2.0 License | Google Research | [GitHub](https://github.com/google-research-datasets/tydiqa) |

### Speech Synthesis

| Name           | Description                                                 | Size    | License         | Creator | Download                                                     |
| -------------- | ----------------------------------------------------------- | ------- | --------------- | ------- | ------------------------------------------------------------ |
| TSync-1 Corpus | Thai speech synthesis corpus from  NECTEC (not full corpus) | 6 hours | CC BY-SA-NC 3.0 | NECTEC  | [Mirror from @korakot: GitHub](https://github.com/korakot/corpus/releases/download/v1.0/TSync1Corpus.zip) |
| TSync-2 Corpus | Thai speech synthesis corpus from  NECTEC (not full corpus) | 5hr 25m | CC BY-SA-NC 3.0 | NECTEC  | [aiforthai](https://aiforthai.in.th/corpus.php) (registration required) and [Mirror from @korakot](https://github.com/korakot/corpus/releases/download/v1.0/AIFORTHAI-TSync2Corpus.zip) |

### Speech Recognition

| Name                | Description                                                  | Size                                | License         | Creator                                                      | Download                                                     |
| ------------------- | ------------------------------------------------------------ | ----------------------------------- | --------------- | ------------------------------------------------------------ | ------------------------------------------------------------ |
| Lotus               | Thai Speech Recognition corpus from NECTEC (not full corpus) | 12 hours                            | CC BY-SA-NC 3.0 | NECTEC                                                       | [aiforthai](https://aiforthai.in.th/corpus.php) (registration required) and [Mirror from @korakot: GitHub](https://github.com/korakot/corpus/releases/download/v1.0/AIFORTHAI-LotusCorpus.zip) |
| Common Voice Corpus | Common Voice Corpus from mozilla                             | 8 hours (valid) and 12 hours (full) | CC0-1.0 License | mozilla                                                      | [Common Voice](https://commonvoice.mozilla.org/th/datasets)  |
| Gowajee corpus      | The corpus was collected in the Automatic Speech Recognition class offered at Chulalongkorn University as a homework assignment. | 11 hours                            | MIT License     | Ekapol Chuangsuwanich, Atiwong Suchato, Korrawe Karunratanakul, Burin Naowarat, Chompakorn CChaichot and Penpicha Sangsa-nga | [GitHub](https://github.com/ekapolc/gowajee_corpus)          |
| Lotus BN            | Thai News Speech Recognition corpus from NECTEC (not full corpus) | 28 minute                           | CC BY-SA-NC 3.0 | NECTEC                                                       | [Mirror from @korakot: GitHub](https://github.com/korakot/corpus/releases/download/v1.0/LOTUS-BN.zip) |
| Lotus Cell          | Thai Speech corpus over the phone. (not full corpus)         | 11 hours                            | CC BY-SA-NC 3.0 | NECTEC                                                       | [Mirror from @korakot: GitHub](https://github.com/korakot/corpus/releases/download/v1.0/LOTUS-cell-v1.0.zip) |

### Plagiarism

| Name            | Description                                                  | Size | License         | Creator | Download                                                     |
| --------------- | ------------------------------------------------------------ | ---- | --------------- | ------- | ------------------------------------------------------------ |
| Thai Plagiarism | Thai Plagiarism Detection http://copycatch.in.th/thai-plagiarism-task.html |      | CC BY-SA-NC 3.0 | NECTEC  | [aiforthai](https://aiforthai.in.th/corpus.php) (registration required) |

### Named Entity Recognition

| Name          | Description                                                  | Size | License         | Creator                     | Download                                                     |
| ------------- | ------------------------------------------------------------ | ---- | --------------- | --------------------------- | ------------------------------------------------------------ |
| นัชชา ถิระสาโรช | corpora by Wirote Aroonmanakun's students                    |      | ?               | นัชชา ถิระสาโรช               | [นัชชา ถิระสาโรช Data](http://pioneer.chula.ac.th/~awirote/Data-Nutcha.zip) |
| ศศิวิมล กาลันสีมา | corpora by Wirote Aroonmanakun's students                    |      | ?               | ศศิวิมล กาลันสีมา               | [ศศิวิมล กาลันสีมา Data](http://pioneer.chula.ac.th/~awirote/Data-Sasiwimon.zip) |
| ณัฐดาพร เลิศชีวะ | corpora by Wirote Aroonmanakun's students                    |      | ?               | ณัฐดาพร เลิศชีวะ               | [ณัฐดาพร เลิศชีวะ Data](http://pioneer.chula.ac.th/~awirote/Data-Nattadaporn.zip) |
| Thai NER      | Thai NER project is part of PyThaiNLP.                       |      | CC BY 3.0       | Wannaphong Phatthiyaphaibun | [GitHub](https://github.com/wannaphong/thai-ner)             |
| THAI-NEST     | Thai Named Entity tagging Corpus from NECTEC & Thammasat University |      | CC BY-SA-NC 3.0 | NECTEC                      | [aiforthai](https://aiforthai.in.th/corpus.php) (registration required) |

### Dictionaries

| Name     | Description                                                  | Size                      | License          | Creator       | Download                                                     |
| -------- | ------------------------------------------------------------ | ------------------------- | ---------------- | ------------- | ------------------------------------------------------------ |
| LEXiTRON | Thai<->English Dictionary                                    | Thai-English 83,000 words | CC BY-SA-NC 3.0  | NECTEC        | [aiforthai](https://aiforthai.in.th/corpus.php) (registration required) |
| Yaitron  | Yaitron English-Thai and Thai-English dictionary based on LEXiTRON created since May 2006. An objective of Yaitron is to built a dictionary that is formatted in well formed XML and easy to be manipulated by machine. |                           | LEXiTRON License | Vee Satayamas | [GitHub](https://github.com/veer66/Yaitron)                  |

### Text Corpus

| Name                     | Description                                                  | Size      | License         | Creator                     | Download                                                     |
| ------------------------ | ------------------------------------------------------------ | --------- | --------------- | --------------------------- | ------------------------------------------------------------ |
| Thai Constitution Corpus | The Constitution of Thailand Dataset Since 1932              |           | Public Domain   | Wannaphong Phatthiyaphaibun | [GitHub](https://github.com/PyThaiNLP/Thai-constitution-corpus) |
| Thai Law                 | Thai Law Dataset (Act of Parliament)                         |           | Public Domain   | Wannaphong Phatthiyaphaibun | [GitHub](https://github.com/PyThaiNLP/thai-law)              |
| IO-LM                    | Learn how to talk like an Information-Operation-er           |           |                 |                             | [GitHub](https://github.com/noppayut/IO-LM)                  |
| HC corpora               | HC corpora is a collection of corpora for various languages freely available to download. homepage : [http://corpora.epizy.com/about.html](http://corpora.epizy.com/about.html) |           |                 |                             | [MediaFire](https://www.mediafire.com/file/1l411ltq14ir3ug/thai_corpus_2012_03_21.rar/file) |
| thai-joke-corpus         | Thai jokes scraped from 4 Thai jokes facebook pages collected by iApp Technology Co, Ltd. | 449 Jokes | GPL-3.0 License | iApp Technology Co, Ltd     | [GitHub](https://github.com/iapp-technology/thai-joke-corpus) |

### N-gram

| Name                       | Description                | Size | License | Creator              | Download                                                     |
| -------------------------- | -------------------------- | ---- | ------- | -------------------- | ------------------------------------------------------------ |
| Unigram from  OSCAR Corpus | Unigram from  OSCAR Corpus |      |         | Korakot Chaovavanich | [Facebook](https://www.facebook.com/groups/colab.thailand/permalink/1524070061101680/) |

### Word Similarity

| Name                                       | Description                                                  | Size | License | Creator                                                    | Download                                                   |
| ------------------------------------------ | ------------------------------------------------------------ | ---- | ------- | ---------------------------------------------------------- | ---------------------------------------------------------- |
| Word Similarity Datasets for Thai Language | This repo contains translated and re-rated datasets for word similarity for Thai language. |      |         | Ponrudee Netisopakul￼, Gerhard Wohlgenannt, Aleksei Pulich | [GitHub](https://github.com/gwohlgen/thai_word_similarity) |

### Grapheme to Phoneme

| Name                | Description                              | Size        | License      | Creator                     | Download                                                     |
| ------------------- | ---------------------------------------- | ----------- | ------------ | --------------------------- | ------------------------------------------------------------ |
| Grapheme to Phoneme | Thai Grapheme to Phoneme from Wiktionary | 14,483 word | CC BY-SA 3.0 | Wannaphong Phatthiyaphaibun | [Facebook](https://www.facebook.com/groups/colab.thailand/permalink/1524070061101680/) |

## Tools

**Menu**

- [Word Segmentation tools](#word-segmentation-tools)
- [Braille](#braille)

### Word Segmentation tools

| Name   | Description                                                  | License | Creator            | Download                                     |
| ------ | ------------------------------------------------------------ | ------- | ------------------ | -------------------------------------------- |
| MudYom | MudYom is a module for pre/post-processing text. It combines, aka มัด, words that should be together into one token. This process is done according to a user-defined dictionary. |         | Pattarawat Chormai | [GitHub](https://github.com/heytitle/mudyom) |

[^ up to menu](#tools)
[^up to top page](#nlp-for-thai)

### Braille

| Name               | Description          | License | Creator | Download                                                 |
| ------------------ | -------------------- | ------- | ------- | -------------------------------------------------------- |
| Thai-textToBraille | Thai text to Braille |         |         | [GitHub](https://github.com/NonKhuna/Thai-textToBraille) |

[^ up to menu](#tools)
[^up to top page](#nlp-for-thai)

## Pre-trained models/Models

**Menu**

[WIP]

... [WIP]