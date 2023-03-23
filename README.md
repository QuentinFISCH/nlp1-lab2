# nlp1-lab2

## Project description

This project is the second lab of the NLP1 course at EPITA. It is about the implementation of a Naive Bayes Classifier for the task of sentiment analysis. The goal is to classify a movie review as positive or negative. The dataset used is the IMDB dataset, which contains 50 000 reviews. The dataset is split into a training set of 25 000 reviews and a test set of 25 000 reviews. The dataset is available at https://ai.stanford.edu/~amaas/data/sentiment/.
We implemented are own Naive Bayes Classifier using lecture notes. We also used the scikit-learn library to compare our results with theirs. Then, we analyzed the results and tried to improve our classifier by using different preprocessing techniques such as Lemmatization and Stemming.

## Submission info

### Group members
- Quentin FISCH
- Théo RIPOLL
- Nicolas FIDEL

LAB02 code is available in the `lab02.ipynb` notebook. It contains the answers to the questions and the code for the experiments, with comments and detailled procedure.

## Setup system:

### Install dependencies

```bash
poetry install
poetry shell
jupyter notebook
```

### To add package
```bash
poetry add <pkg>
```
