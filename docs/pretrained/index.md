# Pre-trained models/Models
[<- back to homepage](../)

**Menu**

- [Text summarization](#text-summarization)
- [Word embeddings](#word-embeddings)
- [Language model](#language-model)
- [Sentence Embedding](#sentence-embedding)
- [Question Answer](#question-answer)
- [Text Generation](#text-generation)

## Text summarization

| Model                | Detail                                                       | Paper                                                        | Download                                                     |
| -------------------- | ------------------------------------------------------------ | ------------------------------------------------------------ | ------------------------------------------------------------ |
| mT5: Multilingual T5 | Multilingual T5 (mT5) is a massively multilingual pretrained text-to-text transformer model, trained following a similar recipe as T5. | [mT5: A massively multilingual pre-trained text-to-text transformer](https://arxiv.org/abs/2010.11934) | [GitHub](https://github.com/google-research/multilingual-t5) |
| BertSum              | Trained Model from Nakhun Chumpolsathien & Tanachat Arayachutinan | Using Knowledge Distillation from Keyword Extraction to Improve the Informativeness of Neural Cross-lingual Summarization | [GitHub](https://github.com/nakhunchumpolsathien/TR-TPBS)    |
| ARedSum              | Trained Model from Nakhun Chumpolsathien & Tanachat Arayachutinan | Using Knowledge Distillation from Keyword Extraction to Improve the Informativeness of Neural Cross-lingual Summarization | [GitHub](https://github.com/nakhunchumpolsathien/TR-TPBS)    |

... [WIP]

## Word embeddings

| Name                           | Detail                                                       | Download                                                     |
| ------------------------------ | ------------------------------------------------------------ | ------------------------------------------------------------ |
| ConceptNet Numberbatch         | ConceptNet Numberbatch is a set of semantic vectors (also known as word embeddings) than can be used directly as a representation of word meanings or as a starting point for further machine learning. | [GitHub](https://github.com/commonsense/conceptnet-numberbatch) |
| FastText Word vectors          | The pre-trained word vectors for 157 languages, trained on Common Crawl and Wikipedia using fastText. | [Website](https://fasttext.cc/docs/en/crawl-vectors.html)    |
| Thai2Fit (old Thai2Vec)        |                                                              | [Homepage](https://github.com/cstorm125/thai2fit)<br />Download word2vec:  [PyThaiNLP](https://github.com/PyThaiNLP/pythainlp-corpus/releases/tag/thai2fit_wv-v0.1) |
| LTW2V: The Large Thai Word2Vec | **LTW2V** is The large Thai Word2Vec. It built with oxidized-thainlp from OSCAR Corpus (Open Super-large Crawled Aggregated coRpus). | [GitHub](https://github.com/PyThaiNLP/large-thaiword2vec)    |

... [WIP]

## Language model

| Name                          | Detail                                                       | Owner                                          | Download                                                     |
| ----------------------------- | ------------------------------------------------------------ | ---------------------------------------------- | ------------------------------------------------------------ |
| Thai2Fit                      | ULMFit Language Modeling, Text Feature Extraction and Text Classification in Thai Language. Created as part of pyThaiNLP with ULMFit implementation from fast.ai | Charin Polpanumas                              | [GitHub](https://github.com/cstorm125/thai2fit)              |
| BERT-th                       | BERT pre-training in Thai language                           | ThAIKeras                                      | [GitHub](https://github.com/ThAIKeras/bert)                  |
| BERT-Base, Multilingual Cased | 104 languages, 12-layer, 768-hidden, 12-heads, 110M parameters | Google                                         | [GitHub](https://github.com/google-research/bert)            |
| bert-base-th-cased            | We are sharing smaller versions of bert-base-multilingual-cased that handle a custom number of languages. | Geotrend                                       | [Hugging Face](https://huggingface.co/Geotrend/bert-base-th-cased) |
| WangchanBERTa                 | Pretraining transformer-based Thai Language Models           | AI Research Institute of Thailand (AIResearch) | [GitHub](https://github.com/vistec-AI/thai2transformers) & [Hugging Face](https://huggingface.co/airesearch) |

### Notebook

- [Load BERT-th, BERT-Base, Multilingual Cased and bert-base-th-cased with Hugging Face in Python](https://colab.research.google.com/drive/1BQ24QBflQujSsi7qjhGfmHn6H_thZvfb?usp=sharing)

## Sentence Embedding

| Name  | Detail                                                       | Paper                                                        | Owner    | Download                                                     |
| ----- | ------------------------------------------------------------ | ------------------------------------------------------------ | -------- | ------------------------------------------------------------ |
| LASER | LASER Language-Agnostic SEntence Representations             | [Massively Multilingual Sentence Embeddings for Zero-Shot Cross-Lingual Transfer and Beyond](https://arxiv.org/abs/1812.10464) | Facebook | [GitHub](https://github.com/facebookresearch/LASER)          |
| MUSE  | Multilingual Universal Sentence Encoderfor Semantic Retrieval | [Multilingual Universal Sentence Encoder for Semantic Retrieval](https://arxiv.org/abs/1907.04307) | Google   | [Tensorflow Hub](https://tfhub.dev/google/universal-sentence-encoder-multilingual-large/3) |
| LaBSE | Language-Agnostic BERT Sentence Embedding by Google AI.      | [Language-agnostic BERT Sentence Embedding](https://arxiv.org/abs/2007.01852) | Google   |                                                              |

## Question Answer


| Name                                      | Detail                                                       | Owner                                       | Download                                                     |
| ----------------------------------------- | ------------------------------------------------------------ | ------------------------------------------- | ------------------------------------------------------------ |
| Zero-shot multilingual QA from DeepPavlov | DeepPavlov is an open-source conversational AI library built on TensorFlow, Keras and PyTorch. | Neural Networks and Deep Learning lab, MIPT | [GitHub](https://github.com/deepmipt/DeepPavlov)<br />[Colab](https://colab.research.google.com/github/deepmipt/dp_tutorials/blob/master/Tutorial_2_DeepPavlov_BERT_transfer_learning.ipynb) |

... [WIP]

## Text Generation

| Name              | Detail                                                       | Owner                       | Download                                                     |
| ----------------- | ------------------------------------------------------------ | --------------------------- | ------------------------------------------------------------ |
| Flax's GPT-2 base | GPT-2 Base Thai is a causal language model based on the OpenAI GPT-2 model. It was trained on the OSCAR dataset, specifically the unshuffled_deduplicated_th subset. The model was trained from scratch and achieved an evaluation loss of 1.708 and an evaluation perplexity of 5.516. | Flax Community              | [Hugging Face](https://huggingface.co/flax-community/gpt2-base-thai) |
| GPT-Neo           | GPT-Neo 1.3B is a transformer model designed using EleutherAI's replication of the GPT-3 architecture. GPT-Neo refers to the class of models, while 1.3B represents the number of parameters of this particular pre-trained model. (It is not training for Thai but It's can working with Thai) | EleutherAI                  | [Hugging Face](https://huggingface.co/EleutherAI)            |
| Thai GPT Next     | It is fine-tune the GPT-Neo model for Thai language.         | Wannaphong Phatthiyaphaibun | [GitHub](https://github.com/wannaphong/thaigpt-next/)        |

