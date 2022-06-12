# Model risks in default probability estimation problems
In this repositary you can find a coding part, which supports the BACHELOR GRADUATION PAPER, made by Lukianov Matvei on the topic of MODEL RISKS IN DEFAULT PROBABILITY ESTIMATION PROBLEMS by supervision of Victor A Lapshin, ICEF, 2022

The code is based, among other things, on the group project made by (c) Anton Markov (@antonitto), Mikhail Baranov (@uasek), Ivan 
Dublenskii (@IvanDublsSt), Ivan Potapov (@Vanaeque), Matvey Lukyanov (@Matteus1904), which can be found [in the corresponding repositary](https://github.com/uasek/credit_scoring_project).

## Repo Structure

`Knn.ipynb` — notebook, estimating preprocessing in KNN model

`LDA.ipynb` — notebook, estimating preprocessing in LDA model

`LGBM.ipynb` — notebook, estimating preprocessing in LGBM model

`Logit.ipynb` — notebook, estimating preprocessing in Logistic regression

`Model_compare.ipynb` — notebook, comparing final performance of models

`requirements.txt` lists all the libraries and versions to set up the virtual environment


## Modules Included

1. Categorical feature encoding
  + WoE encoding
  + OneHot encoding
2. Scaling
  + Standard scaling
  + Robust scaling
  + Minimax Scaling
3. Variable transformation
  + BoxCox
  + Logit
  + YeoJohnson
  + Power Transformer
  + Winsorizer
5. Target imbalance correction
  + Undersampling
  + Oversampling
  + SMOTE
  + ADASYN
6. Feature Selection:
