# CATZ

This is a Weights & Biases community benchmark for machine learning approaches to predict the behavior of catz.

1. Be sure to [sign up](https://app.wandb.ai/login?signup=true) for W&B.
2. Clone this repository: `git clone https://github.com/wandb/catz.git`.
3. Run train.py to train a basic model. Modify this file and the data pipeline (or write your own scripts and create different model architectures) to get better results.
4. Submit your result to the [benchmark](https://app.wandb.ai/wandb/catz/benchmark).

![catz](https://www.americanhumane.org/app/uploads/2016/08/animals-cats-cute-45170-min-1024x569.jpg)

## The dataset

The dataset is comprised of sequences extracted from GIFs of cats thanks to [GIPHY](https://giphy.com)! Each cat has it's own directory and contains a sequence of 6 images. There are 6421 sequences in the training set, and 1475 in the test set. The images are 96x96 pixels.

![catz](https://storage.googleapis.com/wandb/catz.jpg)

## The goal

The goal is to predict the 6th frame given 5 consecutive previous frames.

## Evaluation

We use a [perceptual distance](https://www.compuphase.com/cmetric.htm) metric (val_perceptual_distance) on the validation set to rank results (lower values are better).

## Submitting your results

You can submit your best runs to our [benchmark](https://app.wandb.ai/wandb/catz/benchmark). More specifically, go the "Runs" table in the "Project workspace" tab of your project.
Hover over the run's name, click on the three-dot menu icon that appears to the left of the name, and select "Submit to benchmark".

## Things to try

- Use an RNN
- Different loss functions
- Data augmentation

## Qualcomm

Participating from Qualcomm? See [this README](QUALCOMM.md) for more details.
