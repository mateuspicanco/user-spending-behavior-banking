# :credit_card: Uncovering User Behavior from Credit Card spending Patterns

This project aims at illustrating different ways of framing User Behavior modeling and Customer Segmentation tasks in traditional industries. In this case, we will apply such techniques to the Banking Industry and, more specifically, Credit Card records (CCRs).

The main idea that the project is based upon the process described in the paper called [Sequences of purchases in credit card data reveal lifestyles in urban populations](https://www.nature.com/articles/s41467-018-05690-8) by Clemente Et al. 

In the paper, researchers talk about using the patterns in sequences of credit card transactions in different Merchant Categories to denote user behavior, which arises from common characteristics of this kind of dataset when compared to natural language corpora. The groups of credit card owners identified by the techniques demonstrated are then verified with known sociodemographic data about the user group.

The approach we will develop in this project follows from the same key characteristics of sequential user spending behavior data. We will explore the artifacts of spending semantics to develop a strong signal of user behavior that does not rely on any kind of direct sociodemographic attribute such as age, gender or income. 

With this, we aim to obtain a fine-grained representation of user behavior that avoids known biases in the banking industry (namely income bias) while still maintaining an useful description of users for decision-making and `Customer Segmentation` tasks. 

# Data Sources
The datasets used in this project are based on the paper called [Synthesizing Credit Card Transactions](https://arxiv.org/abs/1910.03033) by IBM researcher Erik R. Altman. All of the datasets are publicly available on [Kaggle](https://www.kaggle.com/ealtman2019/credit-card-transactions) for download.

The Credit Card records data spans over 15 years of synthetic and realistic credit card records for `2000` distinct users that are modeled after US census demographics. 

# Relevant files
- [] Write relevant files

# Main technologies used in this project
1. Data Processing: `Apache Spark`, `pandas`, `numpy`;
2. Data Visualization: `plotly`, `seaborn`, `matlotlib`'
3. Modeling: `gensim`, `umap`, `hdbscan`, `sklearn`;
4. Versioning: `dvc`;