# Machine Learning Projects

Hands-on projects covering the core supervised and unsupervised learning methods, written in Python with
**pandas, seaborn and scikit-learn**. Each project goes from exploratory analysis to model evaluation and ends with
a written interpretation of the results.

I am a statistics student at Eskişehir Osmangazi University and built these projects while working through a data
science and machine learning bootcamp, extending the exercises with my own analysis.

## Projects

| # | Method | Problem | Key result |
|---|---|---|---|
| 01 | [Linear Regression](01-linear-regression/) | Which customer behaviour drives yearly spend: app or website? | R² = 0.99; app time adds ~$39/yr per unit vs. $0.19 for the website |
| 02 | [Logistic Regression](02-logistic-regression/) | Will a user click on an online ad? | 97% accuracy on unseen users |
| 03 | [K-Nearest Neighbors](03-k-nearest-neighbors/) | Choosing K with the elbow method | Accuracy 72% → 84% by tuning K |
| 04 | [Decision Tree & Random Forest](04-decision-tree-random-forest/) | Predicting loans that are not repaid; is accuracy enough? | Class weighting raises bad-loan recall from 2% to 40% |
| 05 | [Support Vector Machines](05-support-vector-machines/) | Classifying iris species, tuning with GridSearchCV | 96% cross-validated accuracy |
| 06 | [K-Means Clustering](06-k-means-clustering/) | Can colleges be split into private/public without labels? | 78% agreement; shows why feature scaling matters |

## Skills shown

- **Data handling:** pandas, dummy encoding, outlier fixing, feature scaling
- **Visualisation:** seaborn / matplotlib (pairplots, joint plots, distribution plots)
- **Modelling:** linear & logistic regression, KNN, decision trees, random forests, SVM, K-Means
- **Evaluation:** train/test split, cross-validation, grid search, confusion matrix, precision / recall / F1, R², RMSE
- **Critical thinking:** class imbalance, overfitting, small-sample instability, interpreting coefficients

## How to run

```bash
git clone https://github.com/mustafaberkkatlav/machine-learning-projects.git
cd machine-learning-projects
pip install -r requirements.txt
jupyter notebook
```

Each folder contains a `notebook.ipynb`, its dataset in `data/`, and a short `README.md`.
All random splits use a fixed `random_state`, so the results can be reproduced.

## Data sources

The datasets come from the *Python for Data Science and Machine Learning Bootcamp* (Pierian Data) and public sources:
Iris (Fisher, 1936), LendingClub loan data (publicly released by LendingClub), Kyphosis (Chambers & Hastie, 1992),
US College data (ISLR, James et al.). The e-commerce, advertising and KNN datasets are synthetic.

## Contact

**Mustafa Berk Katlav**: [GitHub](https://github.com/mustafaberkkatlav)
