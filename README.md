# Siamese Deep Neural Networks for Stereo Matching
A Tensorflow implementation of the models described in the paper [Efficient Deep Learning for Stereo Matching](https://www.cs.toronto.edu/~urtasun/publications/luo_etal_cvpr16.pdf).
This implementation is based on the one provided by the authors of the paper 
at: https://bitbucket.org/saakuraa/cvpr16_stereo_public/overview

win37_dep9 architecture example:
![](figures/win_37_dep9_graph.png)

Current results using win19_dep9 and win37_dep9 architectures, trained over 24 000 training steps (batch size = 128).

| Network  | Val. >3 error | Test >3 error | Runtime (sec.) |
| ------------- | ------------- |------------- | ------------- |
| win19_dep9   |  10.00 | x   |  x |
| win37_dep9  | 7.59  | y   |  x |


Cross-entropy Loss evolution (horizontal axes represent the the number of iterations * 100):
(green=win19_dep9, yellow=win37_dep9)

![](figures/loss.png)




