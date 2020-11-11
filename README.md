# CIFAR10 challange logging with wandb
Pushin' the limits of CIFAR10..

`pip install -r requirements.txt`

pytorch>=1.6

# Usage
Normal: 
`python train_cifar10.py --net res18 --cos`

Gets about 93% Acc.

RandomAug: `python train_cifar10.py --net res18 --aug --n_epoch 200 --cos`

Gets about 94% Acc.
