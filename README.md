# NLP For Thai

It's Thai NLP homepage. All is Open Source. [Work in process...]

## Software

### Word Segmentation

| Name                                                | Description                                                  | Status   | Language       | License                    |
| --------------------------------------------------- | ------------------------------------------------------------ | -------- | -------------- | -------------------------- |
| [libthai](https://github.com/tlwg/libthai)          | is a set of Thai language support routines aimed to ease developers' tasks to incorporate Thai language support in their applications. | active   | C/C++          | LGPL-2.1 License           |
| [SWATH](https://github.com/tlwg/swath)              | Smart Word Analysis for THai                                 | active   | C/C++          | GPL-2.0 License            |
| [AttaCut](https://github.com/PyThaiNLP/attacut)     | Fast and Reasonably Accurate Word Tokenizer for Thai.        | active   | Python 3.X     | MIT License                |
| [PyThaiNLP](https://github.com/PyThaiNLP/pythainlp) | It's part of PyThaiNLP.                                      | active   | Python 3.X     | Apache License 2.0         |
| [PyWordCut](https://github.com/veer66/wordcutpy)    | wordcutpy is a simple Thai word breaker written in Python 3+ | active   | Python 3.X     | LGPLv3                     |
| [DeepCut](https://github.com/rkcosmos/deepcut)      | A Thai word tokenization library using Deep Neural Network.  | active   | Python 3.X     | MIT License                |
| [TLTK](https://pypi.org/project/tltk/)              | Thai Language Toolkit                                        | active   | Python 3.X     | BSD License (BSD-3-Clause) |
| [KUCut](https://github.com/Thanabhat/KUCut)         | Thai word segmentor that is difference from existing segmentor such as CTTEX or SWATH. | deactive | Python 2.4-2.5 | GPL-2.0 License            |
| [SEFR CUT](https://github.com/mrpeerat/SEFR_CUT)    | Stacked Ensemble Filter and Refine for Word Segmentation     | active   | Python 3.X     | MIT License                |

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

## Corpus/Data set

### Word Segmentation Corpus

| Name                                           | Description                                                  | Size                                                         | License                                    | Creator                                                      | Download                                                     |
| ---------------------------------------------- | ------------------------------------------------------------ | ------------------------------------------------------------ | ------------------------------------------ | ------------------------------------------------------------ | ------------------------------------------------------------ |
| BEST I (BEST 2009)                             | Benchmark for Enhancing the Standard of Thai language processing |                                                              | CC BY-SA-NC 4.0                            | NECTEC                                                       | [aiforthai](https://aiforthai.in.th/corpus.php) (registration required) and [Mirror from @korakot](https://github.com/korakot/corpus/tree/main/BEST) |
| LST20 Corpus                                   | LST20 is a large-scale corpus with multiple layers of linguistic annotation for Thai language processing. | 3,164,864 words, 288,020 named entities, 248,962 clauses, and 74,180 sentences | ? (Free for research and open source only) | NECTEC                                                       | [aiforthai](https://aiforthai.in.th/corpus.php) (registration required) |
| Wisesight Samples with Word Tokenization Label | This directory contains samples of Thai social media text, tokenized by humans. These samples are randomly drawn from the full Wisesight Sentiment Corpus. | 160 sentences (wisesight-160) and 1,000 sentences (wiseight-1000) | CC0-1.0 License                            | Nitchakarn Chantarapratin, Pattarawat Chormai, Ponrawee Prasertsom, Jitkapat Sawatphol, Nozomi Yamada, and Attapol Rutherford | [GitHub](https://github.com/PyThaiNLP/wisesight-sentiment/tree/master/word-tokenization) |
| Thai National Historical Corpus (TNHC)         | texts from Thai National Historical Corpus, stored by lines (manually tokenized). | 47 documents, 756,478 lines, 13,361,142 characters           |                                            | Jitkapat Sawatphol                                           | [GitHub](https://github.com/jitkapat/thailitcorpus/releases/tag/v.1.0) |
| Orchid Corpus                                  | Thai partof-speech (POS) tagged corpus                       |                                                              |                                            | NECTEC                                                       |                                                              |

### Parallel Corpus

| Name              | Description                                                  | Size                    | License      | Creator                                                      | Download                                                     |
| ----------------- | ------------------------------------------------------------ | ----------------------- | ------------ | ------------------------------------------------------------ | ------------------------------------------------------------ |
| TALPCo            | TUFS Asian Language Parallel Corpus                          | 1,327 sent              | CC BY 4.0    | Nomoto, Hiroki, Kenji Okano, Sunisa Wittayapanyanon and Junta Nomura | [GitHub](https://github.com/matbahasa/TALPCo)                |
| scb-mt-en-th-2020 | English-Thai Machine Translation Dataset with the collaboration between Vidyasirimedhi Institute of Science and Technology (VISTEC) and Digital Economy Promotion Agency (depa), publishes an open English-Thai machine translation dataset, with the sponsorship from Siam Commercial Bank (SCB) | 1,001,752 segment pairs | CC BY-SA 4.0 | AI Research Institute of Thailand (AIResearch)               | [GitHub](https://github.com/vistec-AI/dataset-releases/releases/tag/scb-mt-en-th-2020_v1.0) |

