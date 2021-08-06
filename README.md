# Yeast DataSet

Code created in the Google Colab repository.

![Open In Colab](https://colab.research.google.com/assets/colab-badge.svg) https://colab.research.google.com/drive/1CZz8T0Jbr2dMxQmzdQB2wuZMv6o6GKJS

## Description of the research problem 

The aim of the work was to demonstrate the influence of the SMOTE class on the accuracy of classification with the use of selected algorithms:
* Support vector machine (SVM)
* K-nearest neighbors (kNN)
* Logistic regression (LR)
* Gaussian Naive Bayes (GNB)

The first stage of the research was the implementation and testing of yeast classification algorithms. In the second stage of the research, the SMOTE class was implemented, which was to equalize the number of instances in each class. Then, after applying SMOTE, a reclassification was made using the same algorithms. The last step was to compare the obtained results and summarize.

The conducted research shows that the SMOTE class, by equalizing the number of occurrences in individual classes, improves the accuracy score for selected algorithms. For the GNB algorithm, the classification accuracy was at the same level. It can be seen that the implemented methods were on average satisfactory with the yeast classification.

## Description of the dataset

Source of [UCI Machine Learning Repository](https://archive.ics.uci.edu/ml/datasets/Yeast)

### Abstract

Predicting the Cellular Localization Sites of Proteins

### Source

Creator and Maintainer:

Kenta Nakai,
Institue of Molecular and Cellular Biology,
Osaka, University,
1-3 Yamada-oka, Suita 565 Japan

### Data Set Information

Predicted Attribute: Localization site of protein ( non-numeric ).

The references below describe a predecessor to this dataset and its development. They also give results (not cross-validated) for classification by a rule-based expert system with that version of the dataset.

Reference: "Expert Sytem for Predicting Protein Localization Sites in Gram-Negative Bacteria", Kenta Nakai & Minoru Kanehisa, PROTEINS: Structure, Function, and Genetics 11:95-110, 1991.

Reference: "A Knowledge Base for Predicting Protein Localization Sites in Eukaryotic Cells", Kenta Nakai & Minoru Kanehisa, Genomics 14:897-911, 1992.

### Attribute Information

1. Sequence Name: Accession number for the SWISS-PROT database
2. mcg: McGeoch's method for signal sequence recognition.
3. gvh: von Heijne's method for signal sequence recognition.
4. alm: Score of the ALOM membrane spanning region prediction program.
5. mit: Score of discriminant analysis of the amino acid content of the N-terminal region (20 residues long) of mitochondrial and non-mitochondrial proteins.
6. erl: Presence of "HDEL" substring (thought to act as a signal for retention in the endoplasmic reticulum lumen). Binary attribute.
7. pox: Peroxisomal targeting signal in the C-terminus.
8. vac: Score of discriminant analysis of the amino acid content of vacuolar and extracellular proteins.
9. nuc: Score of discriminant analysis of nuclear localization signals of nuclear and non-nuclear proteins.
