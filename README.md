# Keras vs. PyTorch: Alien vs. Predator recognition with transfer learning

![](images/transfer_learning.png)


Featured in [deepsense.ai](https://deepsense.ai/) blog post [Keras vs. PyTorch: Alien vs. Predator recognition with transfer learning](https://deepsense.ai/keras-vs-pytorch-avp-transfer-learning), in which we discuss the differences. Code is in two Jupyter Notebooks:

* [Transfer learning with ResNet-50 in Keras](Keras-Resnet50.ipynb)
* [Transfer learning with ResNet-50 in PyTorch](PyTorch-Resnet50.ipynb)

See also the [upcoming webinar (10 Oct 2018)](https://www.crowdcast.io/e/KerasVersusPyTorch/register), in which we walk trough the code.

For plug&play interactive code, see the [Neptune versions with fancy charts](https://app.neptune.ml/deepsense-ai/Keras-vs-PyTorch) or these Kaggle Kernels:

* [Transfer learning with ResNet-50 in Keras - Kaggle Kernel](https://www.kaggle.com/pmigdal/transfer-learning-with-resnet-50-in-keras)
* [Transfer learning with ResNet-50 in PyTorch - Kaggle Kernel](https://www.kaggle.com/pmigdal/transfer-learning-with-resnet-50-in-pytorch)

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

# Webinar info

* [Link do the webinar (10 Oct 2018, 5 PM CEST)](https://www.crowdcast.io/e/KerasVersusPyTorch/register)
* [Slides from the webinar](https://docs.google.com/presentation/d/1y6KBgVtvZ26afCbIbCoGZoEdT6-eoUqPc9U4cJ3X1Gw)
* deepsense.ai's articles about Keras and PyTorch: [article1](https://deepsense.ai/keras-or-pytorch/), [article2](https://deepsense.ai/keras-vs-pytorch-avp-transfer-learning/)
* [notebooks in Neptune](https://app.neptune.ml/deepsense-ai/Keras-vs-PyTorch)
