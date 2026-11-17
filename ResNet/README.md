# ResNet-18: Ants vs. Bees

Transfer learning with a frozen ImageNet-pretrained ResNet-18 backbone and a two-class classifier in PyTorch.

Open [ResNet.ipynb](ResNet.ipynb) in Jupyter or Google Colab and run the cells in order. Requirements: PyTorch, TorchVision, Matplotlib, and Pillow. The first run downloads data and model weights; a CUDA GPU is optional.

The saved run achieved 96.1% validation accuracy (147/153) after four epochs on 244 training images. This is a recorded validation result, not an independent test-set score.
