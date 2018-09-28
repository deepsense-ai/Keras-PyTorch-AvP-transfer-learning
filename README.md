<img src="https://gist.githubusercontent.com/jakubczakon/10e5eb3d5024cc30cdb056d5acd3d92f/raw/5c464c16ccbc7150b4025e0a2a05b84ab99a7bc3/logo_DS_AI.png" alt="Drawing" style="width: 600px;"/>

# Keras vs. PyTorch - Alien vs. Predator recognition with transfer learning

![](images/transfer_learning.png)


Featured in deepsense.ai's blog post [Keras vs. PyTorch - Alien vs. Predator recognition with transfer learning](https://deepsense.ai/keras-vs-pytorch-alien-vs-predator-recognition-with-transfer-learning), in which we discuss the differences. Code is in two notebooks:

* [Transfer learning with ResNet-50 in Keras](https://github.com/buus2/keras_pytorch_01/blob/master/Keras-Resnet50.ipynb)
* [Transfer learning with ResNet-50 in PyTorch](PyTorch-Resnet50.ipynb)

See also the [upcoming webinar (10 Oct 2018)](https://www.crowdcast.io/e/KerasVersusPyTorch/register), in which we walk trough the code.

# Data

See also: [Alien vs. Predator images | Kaggle](https://www.kaggle.com/pmigdal/alien-vs-predator-images).
In general, there are 447 images for each class, split into two classes. Examples:

![](images/example.png)

# Requirements

If you want to run the code, see the requirements:

* Common:
  * jupyter==1.0.0
  * matplotlib==2.2.3
  * Pillow==5.2.0
  * h5py==2.8.0
* Keras:
  * tensorflow==1.10.1
  * Keras==2.2.2
* PyTorch:
  * torch==0.4.1
  * torchvision==0.2.1


