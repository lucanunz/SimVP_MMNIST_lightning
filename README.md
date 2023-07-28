# SimVP_MMNIST_lightning
<a target="_blank" href="https://colab.research.google.com/github/lucanunz/SimVP_MMNIST_lightning/blob/main/notebook/SimVP_MMNIST_lightning.ipynb">
  <img src="https://colab.research.google.com/assets/colab-badge.svg" class="center" alt="Open In Colab"/>
</a>

PyTorch lightning implementation of SimVP architecture. The Colab Notebook contains an implementation of [SimVPv2](https://arxiv.org/abs/2211.12509), [SimVP](https://arxiv.org/abs/2206.05099), and an instantiation of SimVPv2 using the [PoolFormer](https://arxiv.org/abs/2111.11418). The dataset used for the experiments is the Moving MNIST, considering sequences 10 input frames and 10 output frames to predict.

Large parts of the non-lightning code are taken from the model zoo of [OpenSTL](https://github.com/chengtan9907/OpenSTL)

A short report is offered in this repository, and below we report the results obtained with the analyzed models.
![results](https://github.com/lucanunz/SimVP_MMNIST_lightning/blob/main/imgs/results.png)
