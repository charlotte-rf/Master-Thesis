# Master-Thesis
"Building machine learning models to classify HSP90 inhibitors"

In this Github repository, Jupyter Notebooks containing the codes that were used to create this master thesis porject as well as the data set, that was created during this project can be found. 

Content - Jupyter Notebooks
1. Distance_Calculation_Classification_GitHub \
    Calculation of a the significant distance as a later on used classificaition criteria. 
2. Feature_Calculation_GitHub \
    Calculation of molecular descriptors using RDKit that are later introduced as the features. 
3. Baseline_GitHubb \
    Baseline models using the DummyClassifier provided by scikit-learn.
4. RF_All_GitHub \
    Building machine learning models using the RandomForestClassifier provided by scikit-learn. The calculation of metrics is performed to evaluate the performance of the built models. Permutation importance, a tool to evaluate the impact of a single feature on the performance of a model is also displayed in this notebook.
5. GridSearch_GitHub \
    Hyperparameter optimization has a large influence on the performance of a model. GridSearchCV offered by scikit-learn displays a tool that searches for the best hyperparameter combination. 
