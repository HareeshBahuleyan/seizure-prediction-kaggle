# Seizure Prediction Kaggle Competition
IPython notebooks for the <a href="kaggle.com/c/melbourne-university-seizure-prediction/">seizure prediction competition</a>.
(one for extracting features from the data provided and another for prediction and tuning the classifier)

#### Features 
Three categories of features.

1. Time Domain
2. Frequency Domain
3. EEG Specific

Classfier Used:
Xtreme Gradient Boosting (<a href="https://github.com/dmlc/xgboost"> XGBoost </a>)

The following steps of data-preprocessing was carried out;

1. <a href="https://docs.scipy.org/doc/scipy-0.18.1/reference/generated/scipy.signal.resample.html"> Re-sampling </a>
2. <a href="http://scikit-learn.org/stable/modules/generated/sklearn.preprocessing.MinMaxScaler.html">MinMax Normalization</a>
3. <a href="http://scikit-learn.org/stable/modules/generated/sklearn.decomposition.PCA.html"> PCA </a>
4. <a href="https://github.com/scikit-learn-contrib/imbalanced-learn/"> SMOTE </a>
