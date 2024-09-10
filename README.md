<h1 align="center">T-Shirt Sleeve Classification using CNN</h1>

<div align="center">

[![Language](https://img.shields.io/badge/Python-darkblue.svg?style=flat&logo=python&logoColor=white)](https://www.python.org)
[![ML Tool](https://img.shields.io/badge/PyTorch-FF6F00.svg?style=flat&logo=pytorch&logoColor=white)](https://www.tensorflow.org/)
[![Framework](https://img.shields.io/badge/sklearn-darkorange.svg?style=flat&logo=scikit-learn&logoColor=white)](https://scikit-learn.org/stable/index.html)
![reposize](https://img.shields.io/github/repo-size/Oyebamiji-Micheal/T-Shirt-Sleeve-Classification-using-Convolutional-Neural-Network)
[![Topic](https://img.shields.io/badge/Deep%20Learning-lightblue.svg?style=flat)]()
[![Model](https://img.shields.io/badge/CNN-lightgreen.svg?style=flat)](https://arxiv.org/abs/1611.04076)

</div>

<h4 align="center">A beginner's approach to deep learning with PyTorch</h4>

<br/>

<img src="images/cover.png">

<h2>Table of Contents</h2>

- [Overview](#overview)
- [Dataset](#dataset)
- [Model](#model)
- [Result](#result)

<a id="overview"></a>
<h2>Overview</h2>
<p align="justify">
This project is a beginner's approach to deep learning with PyTorch - so nothing too fancy like transfer learning 😐, regularization 😑 or pre-trained models 🙁. The project aims to classify the sleeves of T-shirts into three categories: full sleeve, half sleeve, and sleeveless. 
</p>

<a id="dataset"></a>
<h2>Dataset</h2>
<p align="justify">
The dataset I used was obtained from <a href="https://www.kaggle.com/datasets/vikram92/classify-sleeves-with-tshirt-images" target="_blank">Kaggle</a>.

It is categorized in 3 classes, each representing a different type of sleeve:

- Full Sleeve: 2118 images
- Half Sleeve: 2670 images
- Sleeveless: 1537 images
</p>

<a id="model"></a>
<h2>Model</h2>
<p align="justify">
The model used in this project consists of three convolutional blocks, each containing two convolutional layers followed by ReLU activation and max pooling. The details of this architecture can be found in the <a href="https://github.com/Oyebamiji-Micheal/T-Shirt-Sleeve-Classification-using-Convolutional-Neural-Network/blob/main/t-shirt-sleeve-classification-using-cnns.ipynb" target="_blank">notebook</a>. 
</p>

<a id="result"></a>
<h2>Result</h2>
<p align="justify">
After training the model, I evaluated its performance on the test set. The model achieved 93% accuracy and 93% F1-score on the test set, which is hmmm somehow impressive.</p>

<img src="images/confusion_matrix.png">

<p align="justify">However, the model does have a hard time differentiating between half sleeve and sleeveless cloths. Not surprising though. What I will try to do next is use some regularization techniques and maybe a pre-trained model.</p>

See you in the next one 🙂
