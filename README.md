# CycleGAN-TF
CycleGAN implementation for TensorFlow

original page:https://junyanz.github.io/CycleGAN/

original paper: https://arxiv.org/pdf/1703.10593.pdf

original implementation: https://github.com/junyanz/pytorch-CycleGAN-and-pix2pix

## usage
Add named folder dataA, dataB, valA and valB. dataA and dataB are used for training. valA and valB are used for test.

After putting these folders, Run "python main.py" starts training.when the training is over,Put folders named testA and testB, and Run "python pred.py testA testB" to test.
