# Missing-values-classification
*July 2023*

Statistical theory applied to accommodate missing data for predictive modeling within a classification framework. Research conducted during my in first year MSc internship at the Laboratoire de Probabilités, Statistique et Modélisation (LPSM) at Sorbonne University.

This research was conducted under the supervision of Alexis Ayme, Claire Boyer, Aymeric Dieuleveut, and Erwan Scornet, with corrections provided by Christine Keribin from Paris-Saclay University.

## Keywords
Missing values, linear discriminant analysis(LDA), missclassification error control, missing completely at random(MCAR), missing not at random(MNAR).

## Abstract
There is a scarcity of methods for predicting outcomes when dealing with missing values.
To address this gap, our study focuses on adapting classical classification algorithms to handle
missing values. We propose decomposing the Bayes classifier on a pattern-by-pattern basis,
thereby defining a specific predictor for each given missing pattern. Firstly, we demonstrate that,
under certain assumptions about the distribution of missing patterns, the Linear Discriminant
Analysis (LDA) model preserves the structure of each individual classifier. Exploiting this
property, we establish certain bounds to quantify the information loss compared to the case
where complete data is available. Furthermore, we ascertain the convergence rate of diverse
data-driven classifiers under various assumptions, ensuring their adaptability to a multitude of
real-world scenarios. Secondly, we prove that, even under typical assumptions about the data, the
logistic model is not preserved on a pattern-wise basis. The focus then shifts to the study of the
perceptron model. In this context, the analysis centers around the linear separability of classes
when missing values are present. The objective is to ensure the convergence of the classical
perceptron algorithm for a given missing pattern. The consistency of this pattern-by-pattern
perceptron, is empirically shown through numerical experiments with datasets that verify the
assumptions of the theoretical results.
