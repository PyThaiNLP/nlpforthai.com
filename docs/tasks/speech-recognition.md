# Speech Recognition

## Automatic Speech Recognition

### Corpus

| Name                | Description                                                  | Size              | License         | Creator                                                      | Download                                                     |
| ------------------- | ------------------------------------------------------------ | ----------------- | --------------- | ------------------------------------------------------------ | ------------------------------------------------------------ |
| Lotus               | Thai Speech Recognition corpus from NECTEC (not full corpus) | 12 hours          | CC BY-SA-NC 3.0 | NECTEC                                                       | [aiforthai](https://aiforthai.in.th/corpus.php) (registration required) and [Mirror from @korakot: GitHub](https://github.com/korakot/corpus/releases/download/v1.0/AIFORTHAI-LotusCorpus.zip) |
| Common Voice Corpus | Common Voice Corpus from mozilla                             | 171 hours (valid) | CC0-1.0 License | mozilla                                                      | [Common Voice](https://commonvoice.mozilla.org/th/datasets)  |
| Gowajee corpus      | The corpus was collected in the Automatic Speech Recognition class offered at Chulalongkorn University as a homework assignment. | 11 hours          | MIT License     | Ekapol Chuangsuwanich, Atiwong Suchato, Korrawe Karunratanakul, Burin Naowarat, Chompakorn CChaichot and Penpicha Sangsa-nga | [GitHub](https://github.com/ekapolc/gowajee_corpus)          |
| Lotus BN            | Thai News Speech Recognition corpus from NECTEC (not full corpus) | 28 minute         | CC BY-SA-NC 3.0 | NECTEC                                                       | [Mirror from @korakot: GitHub](https://github.com/korakot/corpus/releases/download/v1.0/LOTUS-BN.zip) |
| Lotus Cell          | Thai Speech corpus over the phone. (not full corpus)         | 11 hours          | CC BY-SA-NC 3.0 | NECTEC                                                       | [Mirror from @korakot: GitHub](https://github.com/korakot/corpus/releases/download/v1.0/LOTUS-cell-v1.0.zip) |
| Thai Elderly Speech dataset by Data Wow and VISAI          | Thai Elderly Speech dataset, consisting of 17 hours 11 minutes (19,200 files). The files are divided into 2 categories: Health care (health issues and services) and Smart Home (using Smart Home devices in household contexts).         | 17 hours 11 minutes          | CC BY-SA 4.0 | VISAI AI Company Limited and Data Wow Company Limited                                                       | [VISAI AI Company Limited and Data Wow Company Limited](https://github.com/VISAI-DATAWOW/Thai-Elderly-Speech-dataset/releases/tag/v1.0.0) |
| FLEURS            | Fleurs is the speech version of the FLoRes machine translation benchmark. We use 2009 n-way parallel sentences from the FLoRes dev and devtest publicly available sets, in 102 languages.  |                            | CC BY      | Google | [huggingface](https://huggingface.co/datasets/google/fleurs)   |
| XTREME-S            | The Cross-lingual TRansfer Evaluation of Multilingual Encoders for Speech (XTREME-S) benchmark is a benchmark designed to evaluate speech representations across languages, tasks, domains and data regimes. It covers 102 languages from 10+ language families, 3 different domains and 4 task families: speech recognition, translation, classification and retrieval.  |                            | CC BY      | Google | [huggingface](https://huggingface.co/datasets/google/xtreme_s)   |
| Thai Dialect Corpus            | Corpus of Central Thai dialect and three other Thai dialects (Khummuang, Korat, and Pattani).  |                            | CC BY-SA 4.0      | Chulalongkorn University | [Github](https://github.com/SLSCU/thai-dialect-corpus)   |


### Software

| Name                                                | Description                                                  | Status | Language   | License            |
| --------------------------------------------------- | ------------------------------------------------------------ | ------ | ---------- | ------------------ |
| [PyThaiASR](https://github.com/PyThaiNLP/pythaiasr) | PyThaiASR is a Python package for Automatic Speech Recognition with focus on Thai language. It have offline thai automatic speech recognition model from Artificial Intelligence Research Institute of Thailand (AIResearch.in.th). | active | Python 3.X | Apache License 2.0 |

### Preatrained

| Name                       | Detail                                                     | Owner                                                        | Download                                                     |
| -------------------------- | ---------------------------------------------------------- | ------------------------------------------------------------ | ------------------------------------------------------------ |
| wav2vec2-large-xlsr-53-th` | Finetuning wav2vec2-large-xlsr-53 on Thai Common Voice 7.0 | Artificial Intelligence Research Institute of Thailand (AIResearch.in.th) | [Hugging Face](https://huggingface.co/airesearch/wav2vec2-large-xlsr-53-th) |
|  Thai Wav2Vec2 with CommonVoice V8 (newmm tokenizer) + language model  | This model trained with CommonVoice V8 dataset by increase data from CommonVoice V7 dataset that It was use in airesearch/wav2vec2-large-xlsr-53-th. It was finetune wav2vec2-large-xlsr-53.| Wannaphong Phatthiyaphaibun | [Hugging Face](https://huggingface.co/wannaphong/wav2vec2-large-xlsr-53-th-cv8-newmm) |
|  Thai Wav2Vec2 with CommonVoice V8 (deepcut tokenizer) + language model   | This model trained with CommonVoice V8 dataset by increase data from CommonVoice V7 dataset that It was use in airesearch/wav2vec2-large-xlsr-53-th. It was finetune wav2vec2-large-xlsr-53.| Wannaphong Phatthiyaphaibun | [Hugging Face](https://huggingface.co/wannaphong/wav2vec2-large-xlsr-53-th-cv8-deepcut) |
| Whisper | Whisper is a general-purpose speech recognition model. (include S2T X->English) | OpenAI | [GitHub](https://github.com/openai/whisper) |


## Language Identification

### Corpus

| Name                | Description                                                  | Size              | License         | Creator                                                      | Download                                                     |
| ------------------- | ------------------------------------------------------------ | ----------------- | --------------- | ------------------------------------------------------------ | ------------------------------------------------------------ |
| VoxLingua107  | VoxLingua107 is a speech dataset for training spoken language  identification models and contains data for 107 languages. (including Thai!!!)  | 61 hours, 5.8G (Thai)  | CC-BY 4.0 License  | Jörgen Valk, Tanel Alumäe.  | [Website](http://bark.phon.ioc.ee/voxlingua107/)  |
