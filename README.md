# SourceBackdoorAttack-Demon
# PAPER
Demon in the Variant Statistical Analysis of DNNs for Robust Backdoor
# DEPENDENCIES
Our code is implemented and tested on Keras with TensorFlow backend. Following packages are used by our code.
1. keras==2.2.2
2. numpy==1.16.0
3. tensorflow-gpu==1.10.1
4. h5py==2.10.0
Our code is tested on Python 3.6.8
# How to use
## TaCT
We implemented our TaCT on one datasets: CIFAR10. The logic is as simple as inject mislabeled trigger-carrying images (poisoned images) together with correctly labeled trigger-carrying images (cover images) into the training set.
## SCAn
SCAn was implemented in SCAn.py, which can get abnormal scores of all classes.
