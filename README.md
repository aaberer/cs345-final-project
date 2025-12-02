# Project Proposal:
## Fairness and Bias Analysis in News Classification
### Project Topic and Motivation
Our proposal is to investigate bias and fairness in machine learning models that have
been trained using news articles. In this study, we will analyze whether machine learning
classifiers behave discriminatorily when identifying political bias across ideological divides. We
are interested in this topic because, although automated content/bias detection algorithms are
being used increasingly in modern applications, they may unintentionally reinforce preexisting
biases. Understanding and addressing these biases is crucial for developing trustworthy and
reliable AI systems.

### Dataset Description
We will use Media Bias/Fact Check (MBFC) Corpus, specifically the ACL2020 version
which consists of:
- 10,000+ news articles from diverse political sources
- Pre-labeled bias annotations (extreme-left, left, center-left, center, center-right, right,
extreme-right)
- Factuality ratings for each source
- Various metadata such as engagement metrics
This dataset fits our use case because it contains current world news articles, with labels from
experts, where fairness disparities have a significant impact on society.

### Methods and Approach
Classification:
1. Baseline Models: Logistic Regression with TF-IDF features
Non-linear Classifiers: SVM with a Radial Basis Function kernel
Fairness analysis:
2. Demographic Equality: Equal prediction rates across political groups
Fairness: Test whether predictions remain consistent when political identifies (i.e.
Democrat is swapped with Republican) are substituted

### Team Responsibilities
Andrews Responsibilities:
1. Text preprocessing pipeline and feature engineering
2. Dataset management and exploration
3. Establish baseline performance metrics
4. Implement fairness metrics
5. Statistical analysis of results

Ethans Responsibilities:
1. Build the SVM model
2. Implement model evaluation and performance comparison
3. Create charts/dashboards for fairness and bias results
4. Conduct demographic equality analysis
5. Document the modeling and analysis workflow
Explanation Methods: Identifying which features drive biased predictions

Joint Responsibilities:
1. Repository and project setup
2. Experimental design and validation strategy
3. Interpretation of fairness findings
4. Writing conclusions
5. Code review and testing
6. Complete project notebook
