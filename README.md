# DeepB3Pred

##Pipeline

###DeepB3Pred uses the following dependencies:

MATLAB2018a 
python 3.10
numpy
scipy *pandas
scikit-learn
catboost= 1.1.1
gc_forset *xgboost-1.5.0
tensorflow=1.15.0
Keras=2.1.6



###Guiding principles:

**The data contains training dataset and testing dataset. Training dataset  TR_BB.fasta includes BBB_pos and BBB_neg training samples. Testing dataset TS_BB includes BBB_pos and BBB_neg testing samples

**Feature_Extraction: CPSR is the implementation of component protein sequence representation. mctd is the implementation of composition-transition and distribution, GSFE is the implementation of Graphical and statistical-based feature engineering.

** Classifier: DeepB3Pred.py is the implementation of proposed method to predict B3PPs  and non-B3PPs.
