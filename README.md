# CS231N_2026

This repository contains my code, notes, and experiment notebooks for the CS231n assignments.

## Repository Structure

```text
assignments/
├── assignment1/
├── assignment2/
└── assignment3/
```

The repository mainly includes:

- assignment notebooks
- implemented Python source files
- supporting scripts and small assets
- personal learning notes and experiment records

## Assignment Overview

### Assignment 1: Image Classification and Fully Connected Networks

Assignment 1 focuses on the fundamentals of image classification and neural network training on CIFAR-10.

- `knn.ipynb`: Implements k-Nearest Neighbor classification, compares two-loop, one-loop, and vectorized distance computations, and uses cross-validation to choose `k`.
- `softmax.ipynb`: Implements Softmax classifier loss and gradients, checks gradients numerically, trains with SGD, tunes hyperparameters, and visualizes learned weights.
- `two_layer_net.ipynb`: Builds a two-layer fully connected neural network, implements forward and backward passes, checks gradients, and trains the model.
- `FullyConnectedNets.ipynb`: Extends the two-layer network into deeper fully connected networks with modular layers, optimization, and regularization.
- `features.ipynb`: Uses hand-crafted image features such as HOG and color histograms for classification and compares them with raw-pixel approaches.

### Assignment 2: CNNs, Normalization, Dropout, PyTorch, and RNN Captioning

Assignment 2 covers core deep learning layers, convolutional networks, PyTorch workflows, and sequence modeling for image captioning.

- `BatchNormalization.ipynb`: Implements batch normalization and related normalization layers, including forward/backward behavior and their effect on training.
- `Dropout.ipynb`: Implements dropout and studies how it regularizes neural networks.
- `ConvolutionalNetworks.ipynb`: Implements convolution and pooling layers, builds CNN classifiers, and explores spatial normalization techniques.
- `PyTorch.ipynb`: Uses PyTorch to define, train, and evaluate neural networks with a modern deep learning workflow.
- `RNN_Captioning_pytorch.ipynb`: Implements image captioning models with recurrent networks such as vanilla RNNs and LSTMs.

### Assignment 3: Transformers, Self-Supervised Learning, Diffusion, CLIP, and DINO

Assignment 3 explores advanced visual recognition, representation learning, and generative modeling.

- `Transformer_Captioning.ipynb`: Implements Transformer-based image captioning with attention, positional encoding, and caption generation.
- `Self_Supervised_Learning.ipynb`: Implements SimCLR-style contrastive self-supervised learning, including data augmentation, projection heads, and contrastive loss.
- `DDPM.ipynb`: Implements denoising diffusion probabilistic models with Gaussian diffusion utilities, a UNet denoiser, sampling, and classifier-free guidance for text-conditioned emoji generation.
- `CLIP_DINO.ipynb`: Experiments with CLIP for zero-shot classification and image retrieval, and explores DINO-style self-supervised visual representations.

## Notes on Datasets

Large datasets and generated data files are not uploaded to this repository. This includes files such as COCO, CIFAR-10 downloaded data, model checkpoints, cache files, and local submission archives.

If you want to run the notebooks locally, please download the required datasets according to the original CS231n assignment instructions or the provided dataset scripts.

## Blog Posts

I also wrote Chinese blog posts on Zhihu to summarize parts of the assignments:

| Assignment | Blog |
|---|---|
| Assignment 1 | [Zhihu Blog](https://zhuanlan.zhihu.com/p/2037454495530103997) |
| Assignment 2 Q1 | [Zhihu Blog](https://zhuanlan.zhihu.com/p/2039004289004216468) |
| Assignment 2 Q2 | [Zhihu Blog](https://zhuanlan.zhihu.com/p/2039651833807889641) |
| Assignment 2 Q3 | [Zhihu Blog](https://zhuanlan.zhihu.com/p/2040016194397263144) |

More assignment notes and blog posts will be updated later.

## Disclaimer

This repository is for personal study and record-keeping. Please follow the course collaboration policy if you are taking CS231n or a related course.
