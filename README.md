This project is on partial membership inference attacks



Steps:
1. First install all the required package by running below command in terminal
pip install dataclasses numpy typing_extensions pandas scikit-learn

2. Then went to any lr/mlp_(datatype)_eval_partial.py for testing
3. Every approach adjustable parameters are highlighed by"--------"
4. when you want to experiemnt on binary dataset and switch to experiment on different classes change the label's cluster_label file to 2, 10, 20, 50, 100 (determined by which labels you want to test on) default using 2 classes at first.

Aware:
1. some approach might take a lot of times to have a successful run due to the the limitations of the approaches
2. For Enumerate features approach the parameter is set to 0.01 due to it's computation complexity, adjust the parameter consiously.
3. For experimenting attack on logistic regression to binary data only use 2 and 10 classes because of unknown techical issue on training attack models

#   U O B - F Y P  
 