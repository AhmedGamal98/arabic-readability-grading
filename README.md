# Arabic Readability Grading

> Predicts the reading level (grade) of Arabic texts using handcrafted linguistic features and machine-learning classifiers.

![Python](https://img.shields.io/badge/Python-3776AB?logo=python&logoColor=white)
![scikit-learn](https://img.shields.io/badge/scikit--learn-F7931E?logo=scikitlearn&logoColor=white)
![NLTK](https://img.shields.io/badge/NLTK-154F5B)
![Jupyter](https://img.shields.io/badge/Jupyter-F37626?logo=jupyter&logoColor=white)

## Overview

1. Read Arabic texts, labelled by grade level, from Word documents (`python-docx`).
2. Clean the text and extract readability features (for example sentence and word lengths) with NLTK.
3. Compare several classifiers: SVM, Random Forest, k-NN, Naive Bayes, Decision Tree and an MLP, plus a GRU neural network.
4. Report accuracy per model and pick the best one.

## Files

| File | Description |
| --- | --- |
| `readability_grade.ipynb` | Feature extraction, model comparison and evaluation |

The text corpus (Word documents) is not included in this repository.

## Run it

```bash
pip install python-docx nltk scikit-learn pandas numpy matplotlib seaborn jupyter
jupyter notebook readability_grade.ipynb
```

## Author

**Ahmed Gamal Saber**, Full-Stack Web Developer & AI Engineer
[LinkedIn](https://linkedin.com/in/ahmed-gamal-saber-382081169) · [GitHub](https://github.com/AhmedGamal98)
