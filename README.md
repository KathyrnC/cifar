# Image classification of CIFAR 10 dataset using PyTorch VGG16 pre-trained with over 92% accuracy
- Dataset: [CIFAR 10](https://www.cs.toronto.edu/~kriz/cifar.html)
- Documentation: [VGG16](https://pytorch.org/vision/main/models/generated/torchvision.models.vgg16.html)
- Hyperparameters:
  - num_epochs = 5
  - batch_size = 40
  - learning_rate = 0.001
  - classes = ('plane', 'car', 'bird', 'cat', 'deer', 'dog', 'frog', 'horse', 'ship', 'truck')

- Model Training:
  - Hardware: Google Colab GPU T4

- Model Testing:
  - Accuracy on the test images: 93.36%
  - Prediction: ![image](https://github.com/KathyrnC/cifar/assets/114298577/35523fe9-34d1-408b-88d0-c2b50de64983)

-References:
  - [Buiminhhien2k (2021)](https://medium.com/@buiminhhien2k/solving-cifar10-dataset-with-vgg16-pre-trained-architect-using-pytorch-validation-accuracy-over-3f9596942861)
  - [Morillo (2020)](https://medium.com/analytics-vidhya/the-transfer-learning-experience-with-vgg16-and-cifar-10-dataset-9b25b306a23f)
  - [Github/rasbt/deeplearning-models](https://github.com/rasbt/deeplearning-models/blob/master/pytorch_ipynb/transfer/transferlearning-vgg16-cifar10-1.ipynb)


