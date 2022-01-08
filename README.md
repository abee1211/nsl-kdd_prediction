# nsl-kdd_prediction
This python notebook lets you visualize the NSL-KDD data set. Clean, apply ML prediction algorithms and analyse performance factors on given dataset
About dataset:
NSL-KDD dataset includes a total of 1,48,517 records. For analysis we've divided it into 80% train 20% test ratio.
Dataset has 43 columns having categorical, discrete, continuous and binary values.

About notebook:
In the first part of our process we include necessary library imports and visualisation of dataset.
Next the data is tranformed into usable form like attack types are mapped to their respective attack class, removal of non-required columns, 
scaling numerical values to have zero mean and unit variance.
Last part includes applying the 4 algorithms and analyze their performance with varying transformations on dataset.
