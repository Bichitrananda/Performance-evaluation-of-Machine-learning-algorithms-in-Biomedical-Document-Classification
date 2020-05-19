# Performance-evaluation-of-Machine-learning-algorithms-in-Biomedical-Document-Classification

Abstract
Document classification is a prevalent task in Natural Language Processing (NLP)
with a broad range of applications in the biomedical domain. In biomedical engineering
categorization of biomedical literature into predefined categories becomes a cumbersome
task. Hence, building an automatic document classifier using Machine Learning (ML)
algorithms for the biomedical databases emerges as a significant task among the
scientific community. In addition, empirical evaluation of these state-of-the-art classifiers
for biomedical document categorization also becomes a thrust area of research. Hence,
this paper examines the deployment of the various forefront ML algorithms in automatic
classification of benchmark biomedical datasets like Bio Creative Corpus III, Farm-Ads,
and TREC 2006 genetics Track. Finally, the performance measures of the ML classifiers
have been evaluated through standard classification metrics like accuracy, precision,
recall, and f1-measure.
Keywords: Machine learning, Deep learning, Text Mining, document classification.
1. Introduction
Biomedical engineering introduces different innovative engineering techniques
and materials in medicine and healthcare for the development of biomedical tools
and technology. In the era of internet-connected devices in every minute, a
tremendous amount of biomedical data is generated with the rapid growth
biomedical technology. In particular, biomedical research publishes a large number
of science journals in electronic text form, and the automatic classification of these
biomedical documents leads to a cumbersome task. Hence, building a classifier for
large-scale biomedical documents plays a vital role. Nevertheless, text document
classification is a prevalent task in NLP with broad applications in the biomedical
domain [1], including biomedical literature indexing [2], automatic diagnosis codes
assignment[3], tweets classification for public health topics [4], patient safety
reports classification[5].
In general, an automatic document classification algorithm assigns a predefined
label to the instances of the text documents (test data set) based on the classifier
developed using ML/DL algorithm. However, the classifier captures the inherent
patterns and relationships from the training data set. The most prominent ML
classifiers [6] found in the literature are Decision Tree (DT), k-Nearest
Neighborhood (KNN), Rocchio(RC), Ridge, Multinomial Naïve Bayes(M_NB),
Bernoulli Naïve Bayes(B_NB) classifier, Support Vector Machine (SVM), PassiveAggressive(PA) classifier, Random forest(RF), Artificial Neural Network (ANN)
including Perceptron (PPN), Stochastic Gradient Descent(SGD) and Back Propagation
neural network(BPN).
In the literature, only a few research attempts have been carried out to empirically
evaluate the ML algorithms on the benchmark biomedical dataset in one platform.
A. M. Cohen developed a replacement classification algorithm by assembling SVM
with rejection sampling and chi-square feature selection technique for automatic 
 International Journal of Advanced Science and Technology
Vol. 29, No. 5, (2020), pp. 5704 - 5716
ISSN: 2005-4238 IJAST 5705
Copyright ⓒ 2020 SERSC
document classification [7]. The TREC 2005 genomics track biomedical dataset was
used to compare the classification performance of the classifier with a different
variant of SVM classifier. H. Almeida, M.J. Meurs, L. Kosseim, G. Butler and A.
Tsang conferred supervised machine learning approaches like Naive Bayes, Support
Vector Machine and provision Model Trees to perform text classification of
PubMed abstracts, to support the triage of documents [8].
A bag-of-concepts representation of documents has been developed and applied
machine learning algorithm like SVM for biomedical document classification [9].
D.B. Nguyen, M. Shenify and H. Al-Mubaid proposed an improved feature weighting
technique for document representation and SVM as a classifier [10]. The proposed
document representation technique provides the best classification performance
compared to the documents represented in bag-of-words or TF-IDF document
representation.
Therefore, the primary aim of this paper is to perform an end-to-end performance
analysis of all the prominent ML algorithms deployed in automatic document
classification of biomedical literature. Besides, the performance measures of the
built-in classifiers are compared and empirically evaluated using well-defined
metrics such as accuracy, precision, recall, and f-measure on the publicly available
different biomedical datasets (BioCreative Corpus III(BC3), Farm-Ads, and TREC
2006 Genomics Track).
