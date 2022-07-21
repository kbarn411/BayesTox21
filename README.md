## Bayesian Belief Networks for predicting toxicity

This notebooks contains small research project about using BBN for multi-output classification task performed on Tox21 dataset.


### Summary

Bayesian Belief Networks (BBN) are a graph structure for representing the relationships in a data set between descriptors and a target variable. This study investigated the use of this algorithm in modeling the Quantitative Structure-Activity Relationship (QSAR) of chemical compounds using toxicity assessment as an example. Selected tests from a database containing toxicity information of 12,000 compounds for 12 different toxicity tests were used. The influence of parameters describing the representation of the compound was checked. In addition, toxicity prediction models were created for selected tests, as well as a model predicting the outcome of several tests simultaneously (multi-target). The results indicate that the obtained models have relatively good accuracy and precision, and the use of multi-target models based on the BBN algorithm can lead to better prediction than while using models for predicting single target variable. 

### Files

- BayesTox.ipynb - notebook containing model for predictions using BBNs
- BayesToxMulti.ipynb - notebook containing model for multi-target predictions using BBNs 
- tox21.sdf - dataset used in this study
- FingerPrintsDrawings.html - generated html file with images of descriptors used in the study

### Methodology
- Tox21 dataset containing toxicity data on 12,000 compounds in 12 toxicity tests
- Molecular fingerprints were used to represent the compounds
- The Bayesian Belief Network (BBN) algorithm was used for modeling
- Data preparation: removing variables with fixed values, splitting into a learning set (80% of the data) and a test set (20%)
- Important descriptors were selected using the entropy based criterion
- Model evaluation metrics: accuracy, AUC, precision. The evaluation was performed on training set (5-fold cross-validation) and test set
- Using the BNLearn (Python) library, shape of the network and its graphical representation were established

For more information about results, code or any other questions feel free to contact me.
