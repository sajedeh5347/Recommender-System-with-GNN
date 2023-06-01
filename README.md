# Recommender-System-with-GNN
These codes are related to my thesis, which we achieved significant performance by slightly changing the codes of the reference article.[https://github.com/Autumn945/MGNN-SPred]

The proposed change in the thesis has been applied using the star_GNN function in the model of the reference article. In fact, by adding this function, the performance of the model has been improved and the fundamental change of the codes has been in this part.

Also, by using this function in the MGNN_SPred algorithm, in addition to improving the performance of the model, the execution time of the algorithm was also reduced because by setting the depth of the graph neural network equal to 1, the complexity of the model was reduced and there was no need to increase the depth of the network to improve the performance.

# Support
-Python version: 3.8.16

-tensorflow version:2.10.0

# Data set
https://s3-eu-west-1.amazonaws.com/yc-rdata/yoochoose-data.7z
## Usage:
-./run_time/data/yc/yoochoose-buys.dat

-./run_time/data/yc/yoochoose-clicks.dat
## command
-preprocessing_data.py

-My_codes_for_training_model.ipynb

