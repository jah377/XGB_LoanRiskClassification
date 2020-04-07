EXECUTIVE SUMMARY:
Online Peer-to-peer (P2P) lending is an innovative channel that connects borrowers who need money with lenders who seek competitive returns on investment. In this blog post, we will discuss the P2P lending business model, focusing on Lending Club which is a leading player in the industry. Furthermore, we will introduce data science techniques such as classification models to help investors generate higher returns by identifying high-risk loans. For low-grade loans (grade D or below), the classifiers are able to improve the average return from -1.4% to 7.6%.

RELATED PROJECT BLOGPOST: https://nycdatascience.com/blog/project/investing-with-lending-club/?preview_id=60935&preview_nonce=2e552362fe&_thumbnail_id=-1&preview=true&aiEnableCheckShortcode=true

FILES WITHIN FOLDER:
1. subsampling_notebook
- Notebook used to subsample original data (~2Gb) down to 5% of accepted loans per month. This was necessary to streamline performance of exploratory data analysis and machine learning

2. eda_miniproject_notebook
- File contains all code used to explore subsampled LendingClub data of accepted loans
- Mini-project includes several case studies to explore the power of diversification and effectiveness of our predictive classifier model
- File produces all figures found in the blog post

3. machine_learning_notebook
- Notebook contains all feature engineer and data prep necessary to train Logistic Regression and XGBoost classification models
- Outputs csv of test data used for the mini-project
