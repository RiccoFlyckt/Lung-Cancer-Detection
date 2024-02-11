# Lung-Cancer-Detection 

This is the github repository corresponding to the article Pulmonologists-Level lung cancer detection based on standard blood test analyses and smoking status using a machine learning approach: A retrospective model development and validation study.

Several steps are needed, in order to setup the experiment and results in this article. The steps are stated below.
1) First, install the required python libraries with the following command: pip install numpy pandas seaborn matplotlib scikit-learn imblearn scipy lightgbm xgboost keras tensorflow shap deslib statsmodels scikit_posthocs orange3==3.30
2) The main.ipynb is the primary notebook that is used to train the models and gather the results. Keep in mind that it is not possible to run this notebook without the two datasets: CombinedDataset.csv and the validation data set ENG_200Samples.csv
4) In the notebook, specifically in the cross validation section, the user must add as a parameter, the desired model they wish to train and evaluate. The models can be found in the Models.py file.
5) Next, all results onwards can be run, without any specified parameters.
