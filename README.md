# eSports Prediction Model Sample

## Summary

This repository contains several files from my eSports prediction project: the ones most relevant to machine learning and working with TensorFlow. The data used by `learning.py` comes from another data-processing submodule which processes a database of competitive matches, events, and players, into training data that can be used to predict the outcome of future matches. I cache much of this processed data, and a lot of the more convoluted code in `learning.py` comes from unpacking and re-processing that cached data, along with splitting off some of it for use in datum-by-datum testing (with the `examine_frame` and `examine_ids`). This repository is intended to show that I have spent a lot of time working with TensorFlow, using features like hyperparam tuning, pruning, along with all sorts of loggers, loss functions, and model construction methods.

## Authors

- Julian George
