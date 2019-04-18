# CATZ

A machine learning contest to predict the behavior of catz.  

1. Be sure to [sign up](https://app.wandb.ai/login?signup=true) for W&B using your corporate email address i.e. (@qualcomm.com)
2. Clone this repository on your laptop or hub instance (if you want access to an instance of jupyterlab email contest@wandb.com) `git clone https://github.com/wandb/catz.git`
3. Run train.py to train a basic model, modify this file and the data pipeline to get better results.
4. Submit your result to the [benchmark](https://app.wandb.ai/wandb/catz/benchmark) to be considered for the contest.

![catz](https://www.americanhumane.org/app/uploads/2016/08/animals-cats-cute-45170-min-1024x569.jpg)

This contest will end on May 31st.  The winner will be announced in a W&B blogpost that describes their model and approach.

* **1st prize:** $1000 Gift Certificate
* **2nd Prize:** $300 Gift Certificate
* **3rd Prize:** $200 Gift Certificate

Each gift certificate will be email to the winner after the contest ends.  The gift certificated can be used on an airline or hotel Company of your choice.

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
