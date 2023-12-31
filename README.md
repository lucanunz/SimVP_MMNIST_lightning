# SimVP_MMNIST_lightning
<a target="_blank" href="https://colab.research.google.com/github/lucanunz/SimVP_MMNIST_lightning/blob/main/notebook/SimVP_MMNIST_lightning.ipynb">
  <img src="https://colab.research.google.com/assets/colab-badge.svg" class="center" alt="Open In Colab"/>
</a>

PyTorch lightning implementation of SimVP architecture. The Colab Notebook contains an implementation of [SimVPv2](https://arxiv.org/abs/2211.12509), [SimVP](https://arxiv.org/abs/2206.05099) (Inception Unet), and an instantiation of SimVPv2 using the [PoolFormer](https://arxiv.org/abs/2111.11418). The dataset used for the experiments is the Moving MNIST, considering sequences of 10 input frames and 10 output frames to predict.

Large parts of the non-lightning code are taken from the model zoo of [OpenSTL](https://github.com/chengtan9907/OpenSTL).

In the following the results obtained with the analyzed models are reported. A deeper and wider model based on the SimVPv2 architecture has been also considered. Further details are available in the report offered in this repository.
<p align="center">
<img src="https://github.com/gianni0907/SimVP_MMNIST_lightning/blob/main/imgs/comparison_table.png" alt="Comparison" width="50%" height="50%" title="Comparison">
</p>

Finally, the following image shows the prediction performances of the models on a test sample
![results](https://github.com/lucanunz/SimVP_MMNIST_lightning/blob/main/imgs/results.png "Results")


Project realized by me (luca.nunziante1999@gmail.com) and Giovanbattista Gravina (gianba.gravina7@gmail.com)
