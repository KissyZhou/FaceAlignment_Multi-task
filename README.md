# FaceAlignment_Multi-task
## trying to reproduce the result of TCDCN, but failed. 

1. I think the model is slightly overfitting, train--1e-4 and val--4e-4. regularzation does not make improvement.

2. the results are poor when come to images cropped by myself(out of test set)

3. some hyperparameters are hard to choose~~~ may be this is another reason of the poor result~~~

## data augmentation

1. random translation, zoom, rotation, noise, blur, flip, constrast jitter used

2. small jitter is good. check out face images after augmentation

## there are some tricks get verified in this experiment...
