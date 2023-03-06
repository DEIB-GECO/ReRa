# Supervised Relevance-Redundancy assessments for feature selection in omics-based classification scenarios
ReRa, a novel method using supervised RElevance-Redundancy Assessments to efficiently improve feature selection. 




## Description
Clinically-relevant classifications tasks based on omics, like expression values, can suffer from uneven class distributions and huge, unbalanced dimensionalities of features, which are often noisy and highly redundant.
Feature selection is fundamental to extract predictive features for robust classification. Yet, canonical filters, which are computationally efficient and scalable, struggle to remove redundancy; conversely, Relevance-Redundancy approaches inspect also feature relationships to minimize global redundancy, but cannot easily scale over huge feature sizes. We propose ReRa, a new efficient Relevance-Redundancy approach including filtering and similarity evaluations based on the supervised information provided by the target classes. ReRa uses both global and class-specific similarity assessments to optimize selection, considering also feature differential behaviours that can improve classification.

## Application use cases
Feature selection using ReRa and other SoA approaches are combined with several Machine Learning classifiers to provide expression-based *intrinsic subyping of Breast Cancer patients* at both gene and isoform levels, leveraging TCGA RNA-seq data (gene and transcript isoform expression data). The two use cases considered represent an insightful example of translational application, taking advantage of ReRa capabilities to investigate and enhance a clinically-relevant patient stratification task, which could be easily applied also to other cancer types and diseases.


## Steps of the Analysis and results
In the notebooks provided, we show the steps performed to preprocess datasets, generate alternative feature spaces, tune and evaluate performances of sevaral classification models. In the vast majority of the assessed cases, ReRa provides classifiers with predictive features that improve their performance in such unbalanced classification scenarios: the results are reported and discussed in the related paper. We include comparisons of the different feature spacs and models and we explore feature importance using Shapley Additive Explanations (SHAP) technique to assess the contribution of different genes and isoforms in the crucial clinical issue of prognostically relevant breast cancer patients stratification.


.
