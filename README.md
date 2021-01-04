## Cloud Classification using Deep-Nets

With the spirit of reproducible research, this repository contains all the codes required to produce the results in the manuscript: 

> Jain, M., Jain, N. and Dev, S.(2021). Improving Cloud Classification using Deep Neural Networks. In: International Geoscience and Remote Sensing Symposium. IEEE. 


The work is done using the Google Colab Framework (with GPU).

## Script/Result Files

+ `swimcat_train.ipynb`: main program. Currently, it loads the data, create dataset splits for deep CNN training, and perform data augmentation over the training set. This is followed by deep CNN training for cloud classification using SWIMCAT dataset[1].
+ `results/loss_log.json`: Log files obtianed during the training process containing loss/accuracy over train/validation sets stored in JSON format for each epoch
+ `results/training_accuracy_characteristics.pdf`: Accuracy characteristic curve over training and validation sets
+ `results/training_loss_characteristics.pdf`: Loss characteristic curve over training and validation sets
+ `results/checkpointWeightsBest.hdf5`: Trained best identified deep CNN model - H5PY file - NOT UPLOADED DUE TO LARGE FILE SIZE

# Reference:
> [1] S. Dev, Y. H. Lee, S. Winkler. Categorization of cloud image patches using an improved texton-based approach. Proc. IEEE International Conference on Image Processing (ICIP), Québec City, Canada, Sep. 27-30, 2015.
