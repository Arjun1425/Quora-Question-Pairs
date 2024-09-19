# Quora Question Pairs



## 1. Business Problem

### 1.1 Description

Quora is a platform designed to share knowledge and connect with people who provide unique insights and high-quality answers. With over 100 million monthly visitors, Quora hosts many similarly worded questions. This leads to two issues:
- Seekers may spend more time finding the best answer.
- Writers may feel the need to answer multiple versions of the same question.

To improve user experience, Quora values canonical questions, which reduce redundancy and provide long-term value to both seekers and writers.

> Credits: [Kaggle](https://www.kaggle.com/c/quora-question-pairs)

### Problem Statement
The task is to:
1. Identify which questions on Quora are duplicates of previously asked questions.
2. Automatically provide answers to questions that have already been answered.
3. Predict whether a pair of questions are duplicates or not.

### 1.2 Sources / Useful Links
- **Competition Source**: [Kaggle Quora Question Pairs](https://www.kaggle.com/c/quora-question-pairs)
- **Discussions**: [Data Analysis & XGBoost Starter Discussion](https://www.kaggle.com/anokas/data-analysis-xgboost-starter-0-35460-lb/comments)
- **Winning Solution & Approaches**: [Dropbox Link](https://www.dropbox.com/sh/93968nfnrzh8bp5/AACZdtsApc1QSTQc7X0H3QZ5a?dl=0)
- **Blog 1**: [Semantic Question Matching with Deep Learning - Quora Engineering](https://engineering.quora.com/Semantic-Question-Matching-with-Deep-Learning)
- **Blog 2**: [Identifying Duplicate Questions on Quora - Towards Data Science](https://towardsdatascience.com/identifying-duplicate-questions-on-quora-top-12-on-kaggle-4c1cf93f1c30)

### 1.3 Real World / Business Objectives and Constraints
- The cost of misclassification can be significant.
- You want a probability score for duplicates, allowing flexibility to choose any threshold.
- No strict latency concerns.
- Interpretability of the model is partially important.
