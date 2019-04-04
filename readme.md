### Basic Naive Bayes Classifier in Python

This approach makes use of pre-labeled data provided by the [Kaggle Classroom spam detection challenge](https://inclass.kaggle.com/c/adcg-ss14-challenge-02-spam-mails-detection/data).

### `naive-bayes` Python 3 Classifier

Python project code in `naive-bayes` is written with Python 3.7.

For setup create a virtualenv with the requirements:

create virtual environment first
```

pip install -r naive-baves/requirements.txt
```

To run the Naive Bayes classifier: 

```
cd naive-bayes
python spam_detector.py
```


Only the corpus of words are used as selectors to determine if an email is spam or ham. 

To prevent words with 0 frequency from miscontruing the results, Laplace smoothing is applied to increment each 0 frequency word to 1.

