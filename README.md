# CIFAR10 challange logging with wandb
Pushin' the limits of CIFAR10..

`pip install -r requirements.txt`

pytorch>=1.6

# Usage
Normal: 
`python train_cifar10.py --net res18 --cos`

Log: https://wandb.ai/arutema47/cifar10-challange/reports/Resnet18-normal-training--VmlldzozMTYwNzk?accessToken=sea1ro706yzv057u1iewgj0e7xu3x6pwqb6fu896rsq0pvfvf55k1hibkm014ah3

Gets about 93% Acc.

RandomAug: `python train_cifar10.py --net res18 --aug --n_epoch 200 --cos`

Gets about 94% Acc.
