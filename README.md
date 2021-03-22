# Knn-intution
The k-nearest neighbors (KNN) algorithm is a simple, supervised machine learning algorithm that can be used to solve both classification and regression problems. It's easy to implement and understand, but has a major drawback of becoming significantly slows as the size of that data in use grows.

# Motivation
Learning Machine learning and trying to understand the parameters in KNN and how they work, since more clusters would lead to overfitting and less would lead to underfitting and generalisation, its one of the most popular unsupervised model as well

# Libraries
import pandas as pd
import numpy as np
import matplotlib.pyplot as plt
import seaborn as sns
%matplotlib inline

Sklearn:
- .neighbours
- model_selection, train_test_split
- metrics

# Conclusion
For this used case atleast we got the confusion matrix, classification_report high for k=7, i.r. 7 neighbours
