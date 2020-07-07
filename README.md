This repository would be updated when the code is open-sourced for the paper 
[Neural Additive Models: Interpretable Machine Learning with Neural Nets](https://arxiv.org/abs/2004.13912).

### Update: The code for NAM models is released at https://github.com/google-research/google-research/tree/master/neural_additive_models. 

Currently, we release the tf.keras.Model (in `models.py`) for NAM which can be simply plugged into any neural network training procedure. We also provide helpers for building a computation graph using NAM for classification/regression problems with tf.compat.v1.

Update (July 7): Added training script for training NAM for a single test/train split.

ETA for release of cross-validation training scripts for replicating paper results : July 25.

