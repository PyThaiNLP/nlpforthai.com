# Text Classification

## Corpus

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



## Software

| Name                                                         | Description                                                  | Status | Language   | License            |
| ------------------------------------------------------------ | ------------------------------------------------------------ | ------ | ---------- | ------------------ |
| [`thai_sentiment`](https://github.com/cstorm125/thai_sentiment) | The naive sentiment classification function based on NBSVM trained on [wisesight_sentiment](https://huggingface.co/datasets/wisesight_sentiment) | active | Python 3.X | Apache License 2.0 |
