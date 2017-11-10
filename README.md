# Sentiment Analysis in Czech
Despite the wealth of state-of-art sentiment analysis solutions and APIs available for mainstream languages like English, there are very few publicly available sentiment analysis experiments in Czech—and a complete lack of implemented examples.

That's why I decided to document my endeavors in this repository. You can find individual attempts in their respective branches; or subdirectories here on `master` if you want to bulk download.

## Attempts
### Sentence-level classification using word embeddings and CNNs
***October 31, 2017 | 3 labels | ~72% accuracy***<br />
The overall goal of this project was to create **a simple sentence-level classifier** that will differentiate between *neutral, negative and positive sentiments.*

It leverages the power of **word embeddings** for representing text data in 100-dimensional vector space and two-layer **convolutional neural network** for extracting features from the encoded text data.

#### [→ Go to `sentence-level` branch](https://github.com/kysely/sentiment-analysis-czech/tree/sentence-level)

---

#### More experiments to come soon.

---

## Licensing
All experiments' code and implementations are licensed under [MIT](https://github.com/kysely/sentiment-analysis-czech/blob/master/LICENSE). However there is some third-party software used. Please pay attention to their licenses.