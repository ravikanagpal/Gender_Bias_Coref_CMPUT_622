# Measuring Gender Bias in Coreference Resolution Systems
## Team
|Student name      | CCID       |
|------------------|------------|
|Ravika Nagpal     |  ravika    |
|Natalie Hervieux  |  nhervieu  |

---
## Execution Instructions
### Run

Use the google colab notebooks provided in src folder to run the two models:

1. E2E model - provided by Allen NLP and based on the work of [Lee, Kenton & He, Luheng & Lewis, Mike & Zettlemoyer, Luke. 2017. End-to-end Neural Coreference Resolution.](https://arxiv.org/pdf/1707.07045.pdf)

2. Neural Coref model - provided by Huggingface and based on the work of  [Kevin Clark and Christopher D. Manning. 2016. Deep reinforcement learning for mention-ranking coreference models. In Empirical Methods on Natural Language Processing.](https://aclanthology.org/D16-1245.pdf)

### Data

The data used can be found in [data](data/) folder

### Output

The output of the run done on gold_BUG dataset is stored in csv files corresponding to each model and can be found in the [output](output/) directory.

---
