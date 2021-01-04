# NLP For Thai

It's Thai NLP homepage. All is Open Source. [Work in process...]

## Software

### Word Segmentation

| Name                                                         | Description                                                  | Status   | Language       | License                    |
| ------------------------------------------------------------ | ------------------------------------------------------------ | -------- | -------------- | -------------------------- |
| [ICU](http://site.icu-project.org/home)                      | ICU - International Components for Unicode                   | active   | C/C++/Java     | Unicode License            |
| [libthai](https://github.com/tlwg/libthai)                   | is a set of Thai language support routines aimed to ease developers' tasks to incorporate Thai language support in their applications. | active   | C/C++          | LGPL-2.1 License           |
| [SWATH](https://github.com/tlwg/swath)                       | Smart Word Analysis for THai                                 | active   | C/C++          | GPL-2.0 License            |
| [AttaCut](https://github.com/PyThaiNLP/attacut)              | Fast and Reasonably Accurate Word Tokenizer for Thai.        | active   | Python 3.X     | MIT License                |
| [PyThaiNLP](https://github.com/PyThaiNLP/pythainlp)          | It's part of PyThaiNLP.                                      | active   | Python 3.X     | Apache License 2.0         |
| [PyWordCut](https://github.com/veer66/wordcutpy)             | wordcutpy is a simple Thai word breaker written in Python 3+ | active   | Python 3.X     | LGPLv3                     |
| [DeepCut](https://github.com/rkcosmos/deepcut)               | A Thai word tokenization library using Deep Neural Network.  | active   | Python 3.X     | MIT License                |
| [TLTK](https://pypi.org/project/tltk/)                       | Thai Language Toolkit                                        | active   | Python 3.X     | BSD License (BSD-3-Clause) |
| [KUCut](https://github.com/Thanabhat/KUCut)                  | Thai word segmentor that is difference from existing segmentor such as CTTEX or SWATH. | deactive | Python 2.4-2.5 | GPL-2.0 License            |
| [SEFR CUT](https://github.com/mrpeerat/SEFR_CUT)             | Stacked Ensemble Filter and Refine for Word Segmentation     | active   | Python 3.X     | MIT License                |
| [CutKum](https://github.com/pucktada/cutkum)                 | Thai Word-Segmentation with LSTM in Tensorflow               |          | Python 3.X     | MIT License                |
| [ThaiLMCut](https://github.com/meanna/ThaiLMCUT)             | Word Tokenizer for Thai Language based on Transfer Learning and bidirectional-LSTM | active   | Python 3.X     | MIT License                |
| [LexTo](http://www.sansarn.com/lexto/)                       | Thai word segmentation ( Longest Matching )                  | -        | Java           | LGPLv2.1                   |
| [sertiscorp /thai-word-segmentation](https://github.com/sertiscorp/thai-word-segmentation) | Thai word segmentation with bi-directional RNN               | -        | Python 3.X     | MIT License                |

### Syllable Segmenter

| Name                                   | Description                     | Status | Language   | License            |
| -------------------------------------- | ------------------------------- | ------ | ---------- | ------------------ |
| [ssg](https://github.com/ponrawee/ssg) | CRF syllable segmenter for Thai | active | Python 3.X | Apache License 2.0 |

### Part Of Speech

| Name                                                | Description             | Status | Language   | License            |
| --------------------------------------------------- | ----------------------- | ------ | ---------- | ------------------ |
| [PyThaiNLP](https://github.com/PyThaiNLP/pythainlp) | It's part of PyThaiNLP. | active | Python 3.X | Apache License 2.0 |

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

## Corpus/Dataset

### Word Segmentation Corpus

| Name                                           | Description                                                  | Size                                                         | License                                    | Creator                                                      | Download                                                     |
| ---------------------------------------------- | ------------------------------------------------------------ | ------------------------------------------------------------ | ------------------------------------------ | ------------------------------------------------------------ | ------------------------------------------------------------ |
| BEST I (BEST 2009)                             | Benchmark for Enhancing the Standard of Thai language processing | 5,000,000 word                                               | CC BY-SA-NC 4.0                            | NECTEC                                                       | [aiforthai](https://aiforthai.in.th/corpus.php) (registration required) and [Mirror from @korakot](https://github.com/korakot/corpus/tree/main/BEST) |
| LST20 Corpus                                   | LST20 is a large-scale corpus with multiple layers of linguistic annotation for Thai language processing. | 3,164,864 words, 288,020 named entities, 248,962 clauses, and 74,180 sentences | ? (Free for research and open source only) | NECTEC                                                       | [aiforthai](https://aiforthai.in.th/corpus.php) (registration required) |
| Wisesight Samples with Word Tokenization Label | This directory contains samples of Thai social media text, tokenized by humans. These samples are randomly drawn from the full Wisesight Sentiment Corpus. | 160 sentences (wisesight-160) and 1,000 sentences (wiseight-1000) | CC0-1.0 License                            | Nitchakarn Chantarapratin, Pattarawat Chormai, Ponrawee Prasertsom, Jitkapat Sawatphol, Nozomi Yamada, and Attapol Rutherford | [GitHub](https://github.com/PyThaiNLP/wisesight-sentiment/tree/master/word-tokenization) |
| Thai National Historical Corpus (TNHC)         | texts from Thai National Historical Corpus, stored by lines (manually tokenized). | 47 documents, 756,478 lines, 13,361,142 characters           |                                            | Jitkapat Sawatphol                                           | [GitHub](https://github.com/jitkapat/thailitcorpus/releases/tag/v.1.0) |
| Orchid Corpus                                  | Thai part of speech (POS) tagged corpus                      | 5,200 sentences                                              | CC BY-SA-NC 4.0                            | NECTEC                                                       | [Mirror from @wannaphong](https://github.com/wannaphong/corpus_mirror/releases/tag/orchid-v1.0) |

### Part of Speech

| Name          | Description                                                  | Size                                                         | License                                    | Creator                | Download                                                     |
| ------------- | ------------------------------------------------------------ | ------------------------------------------------------------ | ------------------------------------------ | ---------------------- | ------------------------------------------------------------ |
| Orchid Corpus | Thai part of speech (POS) tagged corpus                      | 5,200 sentences                                              | CC BY-SA-NC 4.0                            | NECTEC                 | [Mirror from @wannaphong](https://github.com/wannaphong/corpus_mirror/releases/tag/orchid-v1.0) |
| LST20 Corpus  | LST20 is a large-scale corpus with multiple layers of linguistic annotation for Thai language processing. | 3,164,864 words, 288,020 named entities, 248,962 clauses, and 74,180 sentences | ? (Free for research and open source only) | NECTEC                 | [aiforthai](https://aiforthai.in.th/corpus.php) (registration required) |
| UD Thai PUD   | This is a part of the Parallel Universal Dependencies (PUD) treebanks created for the CoNLL 2017 shared task on Multilingual Parsing from Raw Text to Universal Dependencies. | 1,000 sentences                                              | CC BY-SA 3.0                               | Universal Dependencies | [GitHub](https://github.com/UniversalDependencies/UD_Thai-PUD) |

### Treebank

| Name | Description                                                  | Size            | License   | Creator                                                      | Download                                    |
| ---- | ------------------------------------------------------------ | --------------- | --------- | ------------------------------------------------------------ | ------------------------------------------- |
| thtb | To enable research oppotunities with very few Thai Computational Linguitic resources, we willingly introduce fundamental high-level language resouces built with passion, Thai Treebanks, build from scratch for researchers and enthusiasts. | 5,200 sentences | CC BY 4.0 | Pechlada Seenual, Thodsaporn Chay-intr and Thanaruk Theeramunkong | [GitHub](https://github.com/tchayintr/thtb) |

### Natural Language Inference

| Name | Description                                                  | Size                           | License      | Creator           | Download                                           |
| ---- | ------------------------------------------------------------ | ------------------------------ | ------------ | ----------------- | -------------------------------------------------- |
| XNLI | The Cross-lingual Natural Language Inference (XNLI) corpus is a crowd-sourced collection of 5,000 test and 2,500 dev pairs for the MultiNLI corpus. The pairs are annotated with textual entailment and translated into 14 languages: French, Spanish, German, Greek, Bulgarian, Russian, Turkish, Arabic, Vietnamese, Thai, Chinese, Hindi, Swahili and Urdu. | 5,000 test and 2,500 dev pairs | CC BY-NC 4.0 | Facebook Research | [GitHub](https://github.com/facebookresearch/XNLI) |

### Parallel Corpus

| Name              | Description                                                  | Size                    | License      | Creator                                                      | Download                                                     |
| ----------------- | ------------------------------------------------------------ | ----------------------- | ------------ | ------------------------------------------------------------ | ------------------------------------------------------------ |
| TALPCo            | TUFS Asian Language Parallel Corpus                          | 1,327 sent              | CC BY 4.0    | Nomoto, Hiroki, Kenji Okano, Sunisa Wittayapanyanon and Junta Nomura | [GitHub](https://github.com/matbahasa/TALPCo)                |
| scb-mt-en-th-2020 | English-Thai Machine Translation Dataset with the collaboration between Vidyasirimedhi Institute of Science and Technology (VISTEC) and Digital Economy Promotion Agency (depa), publishes an open English-Thai machine translation dataset, with the sponsorship from Siam Commercial Bank (SCB) | 1,001,752 segment pairs | CC BY-SA 4.0 | AI Research Institute of Thailand (AIResearch)               | [GitHub](https://github.com/vistec-AI/dataset-releases/releases/tag/scb-mt-en-th-2020_v1.0) |

### Text Classification

| Name                          | Description                                                  | Size                             | Labels | License          | Creator                                                      | Download                                                     |
| ----------------------------- | ------------------------------------------------------------ | -------------------------------- | ------ | ---------------- | ------------------------------------------------------------ | ------------------------------------------------------------ |
| prachathai-67k                | News Article Corpus from Prachathai.com                      | 67,889 articles wtih 51,797 tags | 12     | CC BY 4.0        | @lukkiddd and @cstorm125                                     | [GitHub](https://github.com/PyThaiNLP/prachathai-67k)        |
| wisesight sentiment           | Social media messages in Thai language with sentiment label (positive, neutral, negative, question). | 26,737 messages                  | 4      | CC0-1.0 License  | Arthit Suriyawongkul,  Ekapol Chuangsuwanich                 | [GitHub](https://github.com/PyThaiNLP/wisesight-sentiment)   |
| wongnai corpus                | This project is a collection of Wongnai's datasets which are mostly in Thai language. | 500K words labeled               | 5      | LGPL-3.0 License | wongnai                                                      | [GitHub](https://github.com/wongnai/wongnai-corpus)          |
| Toxicity in Thai Tweet Corpus | Toxicity in Thai Tweet Corpus                                | 3,300 messages                   | 2      | CC BY-NC 4.0     | Tokyo Metropolitan University Natural Language Processing Group | [GitHub](https://github.com/tmu-nlp/ThaiToxicityTweetCorpus) |

### OCR Dataset

| Name                  | Description                                | Size | License         | Creator                 | Download                                                     |
| --------------------- | ------------------------------------------ | ---- | --------------- | ----------------------- | ------------------------------------------------------------ |
| KVIS Thai OCR Dataset | Offline Thai Handwritten Character Dataset |      | CC BY  4.0      | John Joseph, Ferdin Joe | [Website](https://data.mendeley.com/datasets/8nr3pbdk5c/1)   |
| Thai OCR              |                                            |      | CC BY-SA-NC 3.0 | NECTEC                  | [aiforthai](https://aiforthai.in.th/corpus.php) (registration required) |

### Text Summarization

| Name    | Description                                      | Size                      | License     | Creator               | Download                                                  |
| ------- | ------------------------------------------------ | ------------------------- | ----------- | --------------------- | --------------------------------------------------------- |
| ThaiSum | The largest dataset for Thai text summarization. | 350,000 articles (2.9 GB) | MIT Licence | Nakhun Chumpolsathien | [GitHub](https://github.com/nakhunchumpolsathien/ThaiSum) |

### Question Answering

| Name    | Description                                                  | Size                                           | License         | Creator  | Download                                                     |
| ------- | ------------------------------------------------------------ | ---------------------------------------------- | --------------- | -------- | ------------------------------------------------------------ |
| XQuAD   | XQuAD (Cross-lingual Question Answering Dataset) is a benchmark dataset for evaluating cross-lingual question answering performance. | 240 paragraphs and 1,190 question-answer pairs | CC BY-SA  4.0   | DeepMind | [GitHub](https://github.com/deepmind/xquad)                  |
| Thai QA | Question answering program from Thai Wikipedia.              | 4,000 question-answer pairs                    | CC BY-SA-NC 3.0 | NECTEC   | Dataset: [aiforthai](https://aiforthai.in.th/corpus.php) (registration required), wiki: [copycatch](http://www.copycatch.in.th/documents-nsc.tar.gz), Sample data set: [copycatch](http://www.copycatch.in.th/qa-output100.json) |

### Speech Synthesis

| Name           | Description                                                 | Size    | License         | Creator | Download                                                     |
| -------------- | ----------------------------------------------------------- | ------- | --------------- | ------- | ------------------------------------------------------------ |
| TSync-1 Corpus | Thai speech synthesis corpus from  NECTEC (not full corpus) | 6 hours | CC BY-SA-NC 3.0 | NECTEC  | [Mirror from @korakot: GitHub](https://github.com/korakot/corpus/releases/download/v1.0/TSync1Corpus.zip) |
| TSync-2 Corpus | Thai speech synthesis corpus from  NECTEC (not full corpus) | 5hr 25m | CC BY-SA-NC 3.0 | NECTEC  | [aiforthai](https://aiforthai.in.th/corpus.php) (registration required) and [Mirror from @korakot](https://github.com/korakot/corpus/releases/download/v1.0/AIFORTHAI-TSync2Corpus.zip) |

### Speech Recognition

| Name                | Description                                                  | Size            | License         | Creator                                                      | Download                                                     |
| ------------------- | ------------------------------------------------------------ | --------------- | --------------- | ------------------------------------------------------------ | ------------------------------------------------------------ |
| Lotus               | Thai Speech Recognition corpus from  NECTEC                  |                 | CC BY-SA-NC 3.0 | NECTEC                                                       | [Mirror from @korakot: GitHub](https://github.com/korakot/corpus/releases/download/v1.0/TSync1Corpus.zip) |
| Common Voice Corpus | Common Voice Corpus from mozilla                             | 8 hours (valid) | CC0-1.0 License | mozilla                                                      | [Common Voice](https://commonvoice.mozilla.org/th/datasets)  |
| Gowajee corpus      | The corpus was collected in the Automatic Speech Recognition class offered at Chulalongkorn University as a homework assignment. | 11 hours        | MIT License     | Ekapol Chuangsuwanich, Atiwong Suchato, Korrawe Karunratanakul, Burin Naowarat, Chompakorn CChaichot and Penpicha Sangsa-nga | [GitHub](https://github.com/ekapolc/gowajee_corpus)          |

### Plagiarism

| Name            | Description                                                  | Size | License         | Creator | Download                                                     |
| --------------- | ------------------------------------------------------------ | ---- | --------------- | ------- | ------------------------------------------------------------ |
| Thai Plagiarism | Thai Plagiarism Detection http://copycatch.in.th/thai-plagiarism-task.html |      | CC BY-SA-NC 3.0 | NECTEC  | [aiforthai](https://aiforthai.in.th/corpus.php) (registration required) |