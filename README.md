# CATZ

A machine learning contest to predict the behavior of catz.

## The dataset

The dataset is comprised of sequences extracted from GIFs of cats thanks to [GIPHY](https://giphy.com)! Each cat has it's own directory and contains a sequence of 6 images. There are 6421 sequences in the training set, and 1475 in the test set. The images are 96x96 pixels.

![catz](https://storage.googleapis.com/wandb/catz.jpg)

## The challenge

The challenge is to predict the 6th frame given 5 consecutive previous frames. The winner of the contest will be judged by the [perceptual distance](https://www.compuphase.com/cmetric.htm) function defined in train.py.

## Submitting your results

You'll can submit your best runs to our [benchmark](https://app.wandb.ai/wandb/catz/benchmark)

## Things to try:

- Use an RNN
- Different loss functions
- Data augmentation
