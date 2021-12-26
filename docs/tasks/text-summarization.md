# Text Summarization

## Corpus

| Name                 | Description                                                  | Size                                              | License         | Creator               | Download                                                     |
| -------------------- | ------------------------------------------------------------ | ------------------------------------------------- | --------------- | --------------------- | ------------------------------------------------------------ |
| ThaiSum              | The largest dataset for Thai text summarization.             | 350,000 articles (2.9 GB)                         | MIT Licence     | Nakhun Chumpolsathien | [GitHub](https://github.com/nakhunchumpolsathien/ThaiSum)    |
| TR-TPBS              | A dataset for Thai text summarization.                       | 310K articles                                     | MIT License     | Nakhun Chumpolsathien | [GitHub](https://github.com/nakhunchumpolsathien/TR-TPBS)    |
| XL-Sum               | This dataset annotated article-summary pairs from BBC News and covers 45 languages ranging from low to high-resource. | 8,268 (for thai)                                  | CC BY-NC-SA 4.0 |                       | [GitHub](https://github.com/csebuetnlp/xl-sum)               |
| ThaiCrossSum Corpora | Th2En & Th2Zh: The large-scale datasets for Thai text cross-lingual summarization | th-en 310,926 articles and th-zh 310,926 articles |                 | Nakhun Chumpolsathien | [GitHub](https://github.com/nakhunchumpolsathien/ThaiCrossSum_Corpora) |

## Pretrained

| Model                | Detail                                                       | Paper                                                        | Download                                                     |
| -------------------- | ------------------------------------------------------------ | ------------------------------------------------------------ | ------------------------------------------------------------ |
| mT5: Multilingual T5 | Multilingual T5 (mT5) is a massively multilingual pretrained text-to-text transformer model, trained following a similar recipe as T5. | [mT5: A massively multilingual pre-trained text-to-text transformer](https://arxiv.org/abs/2010.11934) | [GitHub](https://github.com/google-research/multilingual-t5) |
| BertSum              | Trained Model by Nakhun Chumpolsathien & Tanachat Arayachutinan | Using Knowledge Distillation from Keyword Extraction to Improve the Informativeness of Neural Cross-lingual Summarization | [GitHub](https://github.com/nakhunchumpolsathien/TR-TPBS)    |
| ARedSum              | Trained Model by Nakhun Chumpolsathien & Tanachat Arayachutinan | Using Knowledge Distillation from Keyword Extraction to Improve the Informativeness of Neural Cross-lingual Summarization | [GitHub](https://github.com/nakhunchumpolsathien/TR-TPBS)    |
| TNCLS                | Trained Model from ThaiCrossSum Corpora by Nakhun Chumpolsathien |                                                              | [GitHub](https://github.com/nakhunchumpolsathien/ThaiCrossSum_Corpora) |
| CLS+MS               | Trained Model from ThaiCrossSum Corpora by Nakhun Chumpolsathien |                                                              | [GitHub](https://github.com/nakhunchumpolsathien/ThaiCrossSum_Corpora) |
| CLS+MT               | Trained Model from ThaiCrossSum Corpora by Nakhun Chumpolsathien |                                                              | [GitHub](https://github.com/nakhunchumpolsathien/ThaiCrossSum_Corpora) |
| XLS – RL-ROUGE       | Trained Model from ThaiCrossSum Corpora by Nakhun Chumpolsathien |                                                              | [GitHub](https://github.com/nakhunchumpolsathien/ThaiCrossSum_Corpora) |