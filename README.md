# ChineseTextCalssification
This project aims to handle classify Chinese document classification problems. Unlike English, whose sentences consist of words separated by blanks and punctuation, Chinese texts consists of characters joined one by one without blanks, and the encoding problem is a little bit complex. And the work:
- Read Chinese texts through 'gbk' encoding method
- Segmented Chinese texts into terms by Jieba package which makes use of CRF.
- Extract features by transforming texts into vectors of TfIdf values of Chinese terms
- Train and classify the texts based on the features extracted above

Environment:
- Python 3.5.2
- Scikit-learn 0.18.2
- numpy

