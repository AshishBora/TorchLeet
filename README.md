# TorchLeet

TorchLeet is a curated set of PyTorch practice problems, inspired by LeetCode-style challenges, designed to enhance your skills in deep learning and PyTorch.

## Table of Contents
- [TorchLeet](#torchleet)
  - [Table of Contents](#table-of-contents)
  - [Getting Started](#getting-started)
    - [1. Install Dependencies](#1-install-dependencies)
    - [2. Structure](#2-structure)
    - [3. How to Use](#3-how-to-use)
  - [Question Set](#question-set)
    - [🟢Easy](#easy)
    - [🟡Medium](#medium)
    - [🔴Hard](#hard)
- [Contribution](#contribution)
- [Authors:](#authors)


**What's cool? 🚀**
- **Diverse Questions**: Covers beginner to advanced PyTorch concepts (e.g., tensors, autograd, CNNs, GANs, and more).
- **Guided Learning**: Includes incomplete code blocks (`...` and `#TODO`) for hands-on practice along with Answers

## Getting Started

### 1. Install Dependencies
- Install pytorch: [Install pytorch locally](https://pytorch.org/get-started/locally/)
- Some problems need other packages. Install as needed.

### 2. Structure
- `<E/M/H><ID>/`: Easy/Medium/Hard along with the question ID.
- `<E/M/H><ID>/qname.ipynb`: The question file with incomplete code blocks.
- `<E/M/H><ID>/qname_SOLN.ipynb`: The corresponding solution file.

### 3. How to Use
- Navigate to questions/ and pick a problem
- Fill in the missing code blocks `(...)` and address the `#TODO` comments.
- Test your solution and compare it with the corresponding file in `solutions/`.

**Happy Learning! 🚀**

## Question Set

### 🟢Easy
1. [Implement linear regression](https://github.com/Exorust/TorchLeet/blob/main/e1/lin-regression.ipynb) [(Solution)](https://github.com/Exorust/TorchLeet/blob/main/e1/lin-regression_SOLN.ipynb)
2. [Write a custom Dataset and Dataloader to load from a CSV file](https://github.com/Exorust/TorchLeet/blob/main/e2/custom-dataset.ipynb) [(Solution)](https://github.com/Exorust/TorchLeet/blob/main/e2/custom-dataset_SOLN.ipynb) 
3. [Write a custom activation function (Simple)](https://github.com/Exorust/TorchLeet/blob/main/e3/custom-activation.ipynb) [(Solution)](https://github.com/Exorust/TorchLeet/blob/main/e3/custom-activation_SOLN.ipynb)
4. [Implement Custom Loss Function (Huber Loss)](https://github.com/Exorust/TorchLeet/blob/main/e4/custom-loss.ipynb) [(Solution)](https://github.com/Exorust/TorchLeet/blob/main/e4/custom-loss_SOLN.ipynb)  
5. [Implement a Deep Neural Network](https://github.com/Exorust/TorchLeet/blob/main/e5/custon-DNN.ipynb) [(Solution)](https://github.com/Exorust/TorchLeet/blob/main/e5/custon-DNN_SOLN.ipynb)  
6. [Visualize Training Progress with TensorBoard in PyTorch](https://github.com/Exorust/TorchLeet/blob/main/e6/tensorboard.ipynb) [(Solution)](https://github.com/Exorust/TorchLeet/blob/main/e6/tensorboard_SOLN.ipynb)  
7. [Save and Load Your PyTorch Model](https://github.com/Exorust/TorchLeet/blob/main/e7/save_model.ipynb) [(Solution)](https://github.com/Exorust/TorchLeet/blob/main/e7/save_model_SOLN.ipynb)  


### 🟡Medium 
1. [Implement an LSTM](https://github.com/Exorust/TorchLeet/blob/main/m1/LSTM.ipynb) [(Solution)](https://github.com/Exorust/TorchLeet/blob/main/m1/LSTM_SOLN.ipynb)  
2. [Implement a CNN on CIFAR-10](https://github.com/Exorust/TorchLeet/blob/main/m2/CNN.ipynb) [(Solution)](https://github.com/Exorust/TorchLeet/blob/main/m2/CNN_SOLN.ipynb)  
3. [Implement an RNN](https://github.com/Exorust/TorchLeet/blob/main/m3/RNN.ipynb) [(Solution)](https://github.com/Exorust/TorchLeet/blob/main/m3/RNN_SOLN.ipynb)  
4. [Use `torchvision.transforms` to apply data augmentation](https://github.com/Exorust/TorchLeet/blob/main/m4/augmentation.ipynb) [(Solution)](https://github.com/Exorust/TorchLeet/blob/main/m4/augmentation_SOLN.ipynb)  
5. [Add a benchmark to your PyTorch code](https://github.com/Exorust/TorchLeet/blob/main/m5/bench.ipynb) [(Solution)](https://github.com/Exorust/TorchLeet/blob/main/m5/bench_SOLN.ipynb)  
6. [Train an autoencoder for anomaly detection](https://github.com/Exorust/TorchLeet/blob/main/m6/autoencoder.ipynb) [(Solution)](https://github.com/Exorust/TorchLeet/blob/main/m6/autoencoder_SOLN.ipynb)  

### 🔴Hard
1. [Write a custom Autograd function for activation (SILU)](https://github.com/Exorust/TorchLeet/blob/main/h1/custon-autgrad-function.ipynb) [(Solution)](https://github.com/Exorust/TorchLeet/blob/main/h1/custon-autgrad-function_SOLN.ipynb)
2. Write a Neural Style Transfer  
3. [Write a Transformer](https://github.com/Exorust/TorchLeet/blob/main/h3/transformer.ipynb) [(Solution)](https://github.com/Exorust/TorchLeet/blob/main/h3/transformer_SOLN.ipynb)  
4. [Write a GAN](https://github.com/Exorust/TorchLeet/blob/main/h4/GAN.ipynb) [(Solution)](https://github.com/Exorust/TorchLeet/blob/main/h4/GAN_SOLN.ipynb)  
5. [Write Sequence-to-Sequence with Attention](https://github.com/Exorust/TorchLeet/blob/main/h5/seq-to-seq-with-Attention.ipynb) [(Solution)](https://github.com/Exorust/TorchLeet/blob/main/h5/seq-to-seq-with-Attention_SOLN.ipynb)  
6. [Quantize your language model](https://github.com/Exorust/TorchLeet/blob/main/h6/quantize-language-model.ipynb) [(Solution)](https://github.com/Exorust/TorchLeet/blob/main/h6/quantize-language-model_SOLN.ipynb)
7. [Enable distributed training in pytorch (DistributedDataParallel)]
8. [Work with Sparse Tensors]
9. [Implement Mixed Precision Training using torch.cuda.amp](https://github.com/Exorust/TorchLeet/blob/main/h9/cuda-amp.ipynb) [(Solution)](https://github.com/Exorust/TorchLeet/blob/main/h9/cuda-amp_SOLN.ipynb)
10. [Add GradCam/SHAP to explain the model.](https://github.com/Exorust/TorchLeet/blob/main/h10/xai.ipynb) [(Solution)](https://github.com/Exorust/TorchLeet/blob/main/h10/xai_SOLN.ipynb)


# Contribution
Feel free to contribute by adding new questions or improving existing ones. Ensure that new problems are well-documented and follow the project structure.

# Authors:

<div align="center">
  <table>
    <tr>
      <td align="center">
        <a href="https://github.com/Exorust">
          <img src="https://avatars.githubusercontent.com/u/20578676?v=4" width="100px;" alt="Chandrahas Aroori"/>
          <br />
          <b>Chandrahas Aroori</b>
        </a>
        <br />
        💻 Developer
      </td>
      <td align="center">
        <a href="https://github.com/CaslowChien">
          <img src="https://avatars.githubusercontent.com/u/99608452?v=4" width="100px;" alt="Caslow Chien"/>
          <br />
          <b>Caslow Chien</b>
        </a>
        <br />
        💻 Developer
      </td>
    </tr>
  </table>
</div>
