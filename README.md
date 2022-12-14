## COMP-576-Final-Project
There are 5 notebooks, one is the visualization of the dataset.

The rest 4 corresponds to a neural network respectively. They include the model itself, the training process, and the testing process.


**dataset2** is the dataset folder:

*test* folder contains the 100 test samples' image.

*train_val* folder contains the 365 train samples' image.

*result.csv* is a sample of the final prediction result, which is used to calculate the AUC score.

*test_val.csv* contains the label of the 100 test samples.

*train_val.csv* contains the label of the 365 train samples.


**sampleWeight** contains two model's weight stored during training:

*dense_weights1210_16k_aug_data.27.h5* is the weight of the 27th epoch training on augmented data using denseNet with k = 16

*inc_weights1211_original_data.12.h5* is the weight of the 12th epoch training on original data using inception Network






