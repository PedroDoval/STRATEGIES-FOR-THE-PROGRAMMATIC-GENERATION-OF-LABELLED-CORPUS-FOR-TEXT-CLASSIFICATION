
# STRATEGIES FOR THE PROGRAMMATIC GENERATION OF LABELLED CORPUS FOR TEXT CLASSIFICATION

Master’s Thesis presented to the Telecommunications Engineering School of the Universidade de Vigo

Master’s Degree in Telecommunications Engineering

Pedro Alonso Doval


## Abstract

This master thesis explores weak supervision technologies, focusing on the more innovative
data programming strategies for automatically labelling large datasets of texts for complex
problems in which human labelling is impractical. The objective of these techniques is
to obtain a training corpus that can be used later for training machine learning models
in text classification problems achieving comparable results to fully supervised models.
To test this approach we selected a real problem: categorizing journalistic news into
multiple predefined categories. This document presents the state of the art about data
programming techniques, and describes the process of designing a solution using the
Snorkel framework. The tasks covered by this master thesis include, first of all, the design
of multiple label functions that serve as weak supervision sources, using an heterogeneous
set of techniques such as heuristics or keyword detection, linear regression classifiers,
clustering methods or deep learning models. Afterwards, the labels of the different sources
are aggregated using a generative model, obtaining probabilistic labels for the news.
Lastly, the final data set is obtained from the probabilistic labels. There is a performance
analysis for different configurations using a crowdsourced dataset as reference. These
results are evaluated to find out the potential applications of data programming techniques
and how to take full advantage of them in practical scenarios.


Keywords:
Natural language processing
Weak Supervision
Data programming
Text classification
Label function