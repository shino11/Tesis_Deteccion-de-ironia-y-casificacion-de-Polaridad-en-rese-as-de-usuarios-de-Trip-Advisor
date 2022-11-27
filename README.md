# Tesis_Deteccion-de-ironia-y-casificacion-de-Polaridad-en-rese-as-de-usuarios-de-Trip-Advisor

In this repository you will find several models for the classification of dialogue acts with and without context. The models were trained with Schema-Guided Dialogue (SGD) data sets and have given acceptable results. The hyperparameters it has are the ones that have offered the best results during the training process.

The dataset used is from the 8th Dialog System Technology Challenge 2019 (https://github.com/google-research-datasets/dstc8-schema-guided-dialogue). These were converted to a multiple csv files.

For words representation, I used the word-embedding model GloVe with 100 dimensions and 6 billion of words:
- https://nlp.stanford.edu/projects/glove/
- https://github.com/stanfordnlp/GloVe

Download and unzip "glove.6B.100d.txt" from https://nlp.stanford.edu/data/glove.6B.zip

Packages used (Python 3.7):
- Tensorflow 2.0
- Scikit-learn 1.0.2
- Pandas 1.3.5
- Numpy 1.21.5
- h5py 2.10.0
