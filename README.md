<p align="center">
  <img src="https://via.placeholder.com/150" alt="Deep Residual Networks Logo" width="150"/>
</p>

<h1 align="center">Deep Residual Networks</h1>

<p align="center">
  <i>"Deep Residual Learning for Image Recognition"</i>
</p>

<p align="center">
  <a href="https://arxiv.org/abs/1512.03385">
    <img src="https://img.shields.io/badge/arXiv-1512.03385-blue" alt="arXiv Paper">
  </a>
  <a href="https://opensource.org/licenses/MIT">
    <img src="https://img.shields.io/badge/license-MIT-green" alt="License">
  </a>
  <a href="https://github.com/KaimingHe/deep-residual-networks">
    <img src="https://img.shields.io/github/stars/KaimingHe/deep-residual-networks?style=social" alt="GitHub Stars">
  </a>
</p>

---

## 🌟 Introduction

This repository contains the original models (ResNet-50, ResNet-101, and ResNet-152) described in the paper ["Deep Residual Learning for Image Recognition"](https://arxiv.org/abs/1512.03385). These models achieved state-of-the-art performance in the following 2015 competitions:

- **ImageNet Classification**
- **ImageNet Detection**
- **COCO Detection**
- **COCO Segmentation**

---

## 🎥 Video Demonstrations

### Overview of Deep Residual Networks

<p align="center">
  <a href="https://youtu.be/example-video1">
    <img src="https://via.placeholder.com/500x300" alt="Deep Residual Networks Video"/>
  </a>
</p>

### Training Visualization

<p align="center">
  <a href="https://youtu.be/example-video2">
    <img src="https://via.placeholder.com/500x300" alt="Training Visualization Video"/>
  </a>
</p>

---

## 📚 Models

### Network Visualizations

- [ResNet-50](http://ethereon.github.io/netscope/#/gist/db945b393d40bfa26006)
- [ResNet-101](http://ethereon.github.io/netscope/#/gist/b21e2aae116dc1ac7b50)
- [ResNet-152](http://ethereon.github.io/netscope/#/gist/d38f3e6091952b45198b)

### Pre-Trained Models

Download the pre-trained model files:

- [MSR Download](http://research.microsoft.com/en-us/um/people/kahe/resnet/models.zip) (deprecated)
- [OneDrive Download](https://onedrive.live.com/?authkey=%21AAFW2-FVoxeVRck&id=4006CBB8476FF777%2117887&cid=4006CBB8476FF777)

---

## 📊 Results

### Training and Validation Curves

<p align="center">
  <img src="https://cloud.githubusercontent.com/assets/11435359/13046277/e904c04c-d412-11e5-9260-efc5b8301e2f.jpg" alt="Training Curves" width="600"/>
</p>

### ImageNet Validation Error Rates

#### 1-Crop Validation

| Model       | Top-1 Error | Top-5 Error |
|-------------|-------------|-------------|
| ResNet-50   | 24.7%       | 7.8%        |
| ResNet-101  | 23.6%       | 7.1%        |
| ResNet-152  | 23.0%       | 6.7%        |

#### 10-Crop Validation

| Model       | Top-1 Error | Top-5 Error |
|-------------|-------------|-------------|
| ResNet-50   | 22.9%       | 6.7%        |
| ResNet-101  | 21.8%       | 6.1%        |
| ResNet-152  | 21.4%       | 5.7%        |

---

## 🛠️ Third-Party Re-Implementations

Here are some notable third-party re-implementations and extensions:

- **Facebook AI Research (FAIR):** [Code](https://github.com/facebook/fb.resnet.torch)
- **Lasagne (CIFAR-10):** [Code](https://github.com/Lasagne/Recipes/tree/master/papers/deep_residual_learning)
- **TensorFlow (CIFAR-10):** [Code](https://github.com/ppwwyyxx/tensorpack/tree/master/examples/ResNet)
- **Keras (ResNet-50):** [Code](https://github.com/raghakot/keras-resnet)

For additional resources, see the [paper](https://arxiv.org/abs/1512.03385).

---

<p align="center">
  Made with ❤️ by [Kaiming He](http://kaiminghe.com) and Team.
</p>
