# Word Segmentation

for Thai language, Word Segmentation is the first step for process Thai text for segment thai text to words.

## Corpus

| Name                                           | Description                                                  | Size                                                         | License                                    | Creator                                                      | Download                                                     |
| ---------------------------------------------- | ------------------------------------------------------------ | ------------------------------------------------------------ | ------------------------------------------ | ------------------------------------------------------------ | ------------------------------------------------------------ |
| BEST I (BEST 2009)                             | Benchmark for Enhancing the Standard of Thai language processing | 5,000,000 word                                               | CC BY-SA-NC 4.0                            | NECTEC                                                       | [aiforthai](https://aiforthai.in.th/corpus.php) (registration required) and [Mirror from @korakot](https://github.com/korakot/corpus/tree/main/BEST) |
| LST20 Corpus                                   | LST20 is a large-scale corpus with multiple layers of linguistic annotation for Thai language processing. | 3,164,864 words, 288,020 named entities, 248,962 clauses, and 74,180 sentences | ? (Free for research and open source only) | NECTEC                                                       | [aiforthai](https://aiforthai.in.th/corpus.php) (registration required) |
| Wisesight Samples with Word Tokenization Label | This directory contains samples of Thai social media text, tokenized by humans. These samples are randomly drawn from the full Wisesight Sentiment Corpus. | 160 sentences (wisesight-160) and 1,000 sentences (wiseight-1000) | CC0-1.0 License                            | Nitchakarn Chantarapratin, Pattarawat Chormai, Ponrawee Prasertsom, Jitkapat Sawatphol, Nozomi Yamada, and Attapol Rutherford | [GitHub](https://github.com/PyThaiNLP/wisesight-sentiment/tree/master/word-tokenization) |
| Thai National Historical Corpus (TNHC)         | texts from Thai National Historical Corpus, stored by lines (manually tokenized). | 47 documents, 756,478 lines, 13,361,142 characters           |                                            | Jitkapat Sawatphol                                           | [GitHub](https://github.com/jitkapat/thailitcorpus/releases/tag/v.1.0) |
| Orchid Corpus                                  | Thai part of speech (POS) tagged corpus                      | 5,200 sentences                                              | CC BY-SA-NC 3.0                            | NECTEC                                                       | [Mirror from @wannaphong](https://github.com/wannaphong/corpus_mirror/releases/tag/orchid-v1.0) |
| Corpus Komped Poem (windy part)                |                                                              |                                                              |                                            | Pattarawat Chormai                                           | [GitHub](https://github.com/PyThaiNLP/corpus-komped-poem-windy-part) |
| VISTEC-TP-TH-21                                | The largest social media domain datasets for Thai text processing (word segmentation, misspell correction and detection, and named-entity boundary) called "VISTEC-TP-TH-2021" or VISTEC-2021. | 49,997 sentences with 3.39M words                            | CC-BY-SA 3.0                               | VISTEC & Chiang Mai University                                                       | [GitHub](https://github.com/mrpeerat/OSKut/tree/main/VISTEC-TP-TH-2021) |


### BEST I

BEST I is the Benchmark for Enhancing the Standard of Thai language processing.

- Number of words: 5,000,000 words

**Details**

- Creator: NECTEC
- License: CC BY-SA-NC 4.0
- Paper:
- Download: [aiforthai](https://aiforthai.in.th/corpus.php) (registration required)

##### Benchmarks

We are not  benchmarks for this corpus because we have not an answer of testset.


### LST20 Corpus

LST20 Corpus is a large-scale corpus with multiple layers of linguistic annotation for Thai language processing.

- Number of words: 3,164,864 words

**Details**

- Creator: NECTEC
- License: (Free for research and open source only)
- Paper: [The Annotation Guideline of LST20 Corpus](https://arxiv.org/abs/2008.05055)
- Download: [aiforthai](https://aiforthai.in.th/corpus.php) (registration required)

##### Benchmarks

[WIP]

### Orchid Corpus

Orchid Corpus is Thai part of speech (POS) tagged corpus with word segmentation corpus.

- Number of words:  words

**Details**

- Creator: NECTEC
- License: CC BY-SA-NC 3.0
- Paper: [Thai Part-of-speech Tagged Corpus: ORCHID](https://www.semanticscholar.org/paper/Thai-Part-of-speech-Tagged-Corpus%3A-ORCHID-Sornlertlamvanich-Takahashi/b2cd2c2b07285f114244a886d02b5b7cb69a203e)
- Download: [Mirror from @wannaphong](https://github.com/wannaphong/corpus_mirror/releases/tag/orchid-v1.0)

##### Benchmarks

Orchid Corpus is not have the testset.


### Wisesight Corpus

This directory contains samples of Thai social media text, tokenized by humans. These samples are randomly drawn from the full Wisesight Sentiment Corpus.

- `wisesight-160` has 160 sentences. Number of words: 3,833 words
- `wiseight-1000` has 1,000 sentences. Number of words: 21,745 words

##### Benchmarks

[WIP]

### Thai National Historical Corpus

Thai National Historical Corpus or TNHC tokenized by humans.

- Number of words:  ? words
- 47 documents, 756,478 lines, 13,361,142 characters

**Details**

- Creator: Jitkapat Sawatphol
- Download: [GitHub](https://github.com/jitkapat/thailitcorpus/releases/tag/v.1.0)

### Corpus Komped Poem (windy part)

- Number of words: 317 words

**Details**

- Creator: Pattarawat Chormai
- License: CC-BY-SA 3.0
- Paper: -
- Download: [GitHub](https://github.com/PyThaiNLP/corpus-komped-poem-windy-part)

##### Benchmarks

[WIP]

### VISTEC-TP-TH-21

The largest social media domain datasets for Thai text processing (word segmentation, misspell correction and detection, and named-entity boundary) called "VISTEC-TP-TH-2021" or VISTEC-2021.

- Number of words: 3.39M words

**Details**

- Creator: VISTEC & Chiang Mai University
- License: CC-BY-SA 3.0
- Paper: -
- Download: [GitHub](https://github.com/mrpeerat/OSKut/tree/main/VISTEC-TP-TH-2021)

## Software

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
| [V8 BreakIterator](https://gist.github.com/korakot/451926b68bc0baab5c9ddb1e28448289) | Chrome's V8 Engine, using ICU  | active   | JavaScript          | Apache License 2.0         |
| [newmm-tokenizer](https://github.com/wisesight/newmm-tokenizer) | Standalone Dictionary-based, Maximum Matching + Thai Character Cluster (newmm) tokenizer extracted from PyThaiNLP. | active   | Python 3.X          | Apache License 2.0         |
| [Stanza](https://github.com/stanfordnlp/stanza)              | Official Stanford NLP Python Library for Many Human Languages | active   | Python 3.X          | Apache License 2.0         |
| [Multi Candidate Thai Word Segmentation](https://github.com/earthy123/Multi-Candidate-Word-Segmentation) | Most existing word segmentation methods output one single segmentation solution. | active   | Python 3.X          | MIT License                |
| [PhlongTaIam](https://github.com/veer66/PhlongTaIam)         | PHP Thai word breaker                                        | active   | PHP                 | LGPL-2.1 License           |
| [Chamkho](https://github.com/veer66/chamkho)         | Rust Thai word breaker                                        | active   | Rust                 | LGPL-3 License           |
| [oxidized-thainlp](https://github.com/PyThaiNLP/oxidized-thainlp) | Thai Natural Language Processing in Rust, with Python-binding. | active | Python & Rust | Apache License 2.0 |
| [OSKut](https://github.com/mrpeerat/OSKut) | Handling Cross- and Out-of-Domain Samples in Thai Word Segmentation (ACL 2021 Findings)<br/>Stacked Ensemble Framework and DeepCut as Baseline model | active | Python | MIT License |

## Tools

| Name   | Description                                                  | License | Creator            | Download                                     |
| ------ | ------------------------------------------------------------ | ------- | ------------------ | -------------------------------------------- |
| MudYom | MudYom is a module for pre/post-processing text. It combines, aka มัด, words that should be together into one token. This process is done according to a user-defined dictionary. |         | Pattarawat Chormai | [GitHub](https://github.com/heytitle/mudyom) |
