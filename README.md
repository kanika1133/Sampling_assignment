# Sampling_assignment

# Comparing Sampling Techniques for 5 Machine Learning Models

## Introduction

This project aims to investigate the efficacy of various sampling techniques for generating a balanced dataset to train a machine learning model. The original dataset is imbalanced, thus, over sampling methods are employed to balance it. After achieving a balanced dataset, four distinct sampling techniques are implemented and the resulting samples are evaluated for accuracy using five different machine learning models.

## Sampling Techniques

1.Simple Random Sampling: A statistical technique where a sample is selected randomly from a given population, with each element in the population having an equal chance of being selected.

2.Stratified Sampling: A method of sampling where a population is divided into mutually exclusive strata based on a specific characteristic, and a random sample is drawn from each stratum in proportion to the size of the stratum.

3.Systematic Sampling: A type of sampling where a sample is selected by following a specific pattern, such as selecting every nth element in the population, where n is a fixed interval.

4.Cluster Sampling: A sampling technique where the population is divided into clusters or groups, and a random sample of the clusters is selected. All members of the selected clusters are included in the sample.


## Comparison Table

The table below shows the accuracies of each sampling technique on five different machine learning models. The dataset used for all models is a balanced version of the original unbalanced dataset using over-sampling techniques.

| Sampling Technique | Logistic Regression | Decision Tree | SVM | Naive Bayes | KNN |
|:---------------:|:---------------:|:---------------:|:---------------:|:---------------:|:---------------:|
| Simple Random Sampling | 86.142322 | **96.254682** | 70.411985 | 81.647940 | 82.771536	 |
| Stratified Sampling | 90.816327 | 93.877551 | 65.306122 | 87.244898 | 78.061224	 |
| Systematic Sampling | 79.220779 | 87.012987 | 66.233766 | 81.818182 | **64.935065** |
| Cluster Sampling | 94.782609 | 94.782609 | 66.086957 | 78.260870 | 75.652174 |

## Conclusion
Based on these results, it can be concluded Systematic random sampling performs the worst on all five models. The other sampling techniques have varying performance depending on the model. The model which gives the best accuracy for all 4 samples is D
