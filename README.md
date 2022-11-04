# Machine-Learning-Pipeline

Automates the entire ML process with a few lines of code

Libraries USED:

nltk
nltk.download(['punkt', 'wordnet', 'averaged_perceptron_tagger'])

re
numpy as np
pandas as pd
from nltk.tokenize import word_tokenize
from nltk.stem import WordNetLemmatizer

from sklearn.metrics import confusion_matrix
from sklearn.model_selection import GridSearchCV
from sklearn.ensemble import RandomForestClassifier
from sklearn.model_selection import train_test_split
from sklearn.pipeline import Pipeline, FeatureUnion
from sklearn.base import BaseEstimator, TransformerMixin
from sklearn.feature_extraction.text import CountVectorizer, TfidfTransformer

This Project covers:
- SKlearns PIPELINE class
- Feature union inorder to transform objects in parallel
- GridSearch to find best hyperparameters
