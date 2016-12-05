# FaceAlignment_Multi-task
## trying to reproduce the result of TCDCN, but failed. 

1. I think the model is just converge at a local optimal, train--15e-4 and val--45e-4. 

2. the results are poor when come to images cropped by myself(out of test set), it may get better result if crop faces use the method as training set,  but i did not have a try.

3. some hyperparameters are hard to choose~~~ may be this is the reason of failure~~~

## data augmentation

1. random translation, zoom, rotation, noise, blur, flip, constrast jitter used

2. small jitter is good. check out face images after augmentation

## there are some tricks get verified in this experiment...
