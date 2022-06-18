## Bayesian Belief Networks for predicting toxicity

This notebooks contains small project about using BBN for multi-output classification task performed on Tox21 dataset.


### Summary

Bayesian Belief Networks (BBNs) are a graph structure for representing the relationships in a data set between descriptors and a target variable. This study investigated the use of this algorithm in modeling the Quantitative Structure-Activity Relationship (QSAR) of chemical compounds using toxicity assessment as an example. Selected tests from a database containing toxicity information of 12,000 compounds for 12 different toxicity tests were used. The influence of parameters describing the representation of the compound was checked. In addition, toxicity prediction models were created for selected tests, as well as a model predicting the outcome of several tests simultaneously (multi-target). The results indicate that the obtained models had relatively good accuracy and precision, and the use of multi-target models based on the BBN algorithm can be beneficial. 

### Files

- BayesTox.ipynb - notebook containing model for predictions using BBNs
- BayesToxMulti.ipynb - notebook containing model for multi-target predictions using BBNs 
- tox21.sdf - dataset used in this study
- FingerPrintsDrawings.html - generated html file with images of descriptors used in the study
