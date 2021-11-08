# TextClassification_with_NLP_and_Fasttext

In this repo, text classification was performed in two different ways on the real-world dataset presented to the competitors in the Doğus Datathon competition, and predictions were made on the test dataset.

## Getting Started

In this project, text classification was done in two different ways. In one method, classification is made using a ready-made fasttext library, while in the second method, the model is trained by creating an LTSM architecture.

### Prerequisites:
- Python 3.x.x
- Keras
- Pandas
- Numpy
- tensorflow 1.x
- Fasttext
- sklearn
- bs4 (for BeautifulSoup)

## ModelwithNLP:
- Data: It consists of three different data sets:train_n11.csv, test_n11.csv and sample_submission_n11.csv.
Columns in the training and test dataset:
 - - ID: Product ID number
- - TITLE: product title
- - DESCRIPTION: Product description in HTML format
- - CATEGORY_ID: Category of the product
Columns in submission dataset:
- - ID: ÜProduct ID number
- - Expected: CATEGORY_ID (Indicates the product category.)
- Type: LTSM
- Optimizer: Adam
- Loss for model: Sparse Categorical Crossentropy

## ModelwithFastext
- Data: Same data
- Type: Fastext(ready library)


## Authors

- [zeynepmerve97](https://github.com/zeynepmerve97) on GitHub
- [Zeynep Merve Arpaç](https://www.linkedin.com/in/zeynep-merve-arpa%C3%A7-4698ba194) on LinkedIn

