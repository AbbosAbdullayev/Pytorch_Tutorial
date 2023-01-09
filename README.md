# Pytorch_Tutorial
Deep learning with PyTorch. We select a PC with GPU (Nvidia RTX). First of all,  create a work environment using anaconda and install all dependencies.

```
conda create -n pytorchlab python=3.7 ## you can select any python version (3.6,3.8 or 3.9)
conda activate pytorchlab # activate anaconda enviroment
conda install pytorch torchvision torchaudio cudatoolkit=11.1 -c pytorch ## cudatoolkit ver also selecting manually
# after the sucsessfull installation
>> python
>> import torch
>> x=torch.rand(4) ## randomly selected tensors
>> print(x)
tensor([0.8975, 0.0306, 0.5966, 0.4856]) ## tensors
>> torch.cuda.is_available() # checking cuda is avialable
True #  gpu supports PyTorch packages
```
