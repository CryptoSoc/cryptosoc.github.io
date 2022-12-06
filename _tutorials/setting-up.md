---
title: Setting up your Environment
author: Thomas Tumiel
layout: tutorials
---

<div class="alert alert-block alert-info">
<h5>Why is this Important:</h5>
Setting up the tools to effectively code can take some time. Here we look at some of the best tools available and recommend you to choose one and get proficient at it. Don't get caught in this stage.
<br />
<strong>Time to read: 15 minutes</strong>
</div>

Code development is as simple as opening a plain text editing program and writing code. There doesn't have to be anything fancy to it. However, often the use of additional tools improves workflow, code readability and code correctness. In this section we explore some of the tools commonly used in blockchain and machine learning development.

If you'd rather just read one of the sections, you can jump to it here:
- [Blockchain Tools](#blockchain-tools)
- [Machine Learning Tools](#machine-learning-tools)

## General Tools

As mentioned before, writing code is as simple as opening up a plain text editor and beginning. But it can be easier. Here, we'll recommend some tools to try out to get you started programming.

### Editors

There is a lot of competition amongst code editors. And I won't say that any one of them is the best. The main thing, however, is to __pick one__ and get good at it. Know the shortcuts, know the tricks. And then it doesn't really matter which one you end up using. If you're not sure or don't feel like really investigating all of them, download [VS Code](https://code.visualstudio.com/) and move on.

Some recommendations:

- [VS Code](https://code.visualstudio.com/)
- [Atom](https://atom.io/)
- [Vim](https://www.vim.org/)
- [Sublime](https://www.sublimetext.com/)
- [PyCharm](https://www.jetbrains.com/pycharm/)

### Version Control

If you went through our [previous Git tutorial](/tutorials/intro-to-git) you'll see that we don't even mention that there are other version control software. It's recommended to stick with Git for now.

There is a small hitch though - Git doesn't always play nice with Windows so if you are on Windows, try use Git Bash which you can choose to install when you install Git.

## Blockchain Tools

This section will focus on developing on the Ethereum platform.

### Developing on Ethereum

The blockchain development landscape is rapidly evolving and new tools are constantly coming out and old ones are being updated. However, this is often not nearly as fast as Ethereum is being updated and changed. A common choice to develop [smart contracts](https://en.wikipedia.org/wiki/Smart_contract), is to use the in-browser IDE, [Remix](https://remix.ethereum.org/), developed by the Ethereum team. It is probably the most useful and up to date development environment you'll find. And fairly easy when you get the hang of it.

### Web3

Web3 is Ethereum's JavaScript API. It allows webapps to interact with the blockchain. To add this functionality to your browser, usually an extension is used like [MetaMask](https://metamask.io/).

### NodeJS and NPM

NodeJS and NPM are javascript tools that make building JavaScript applications much easier. NPM comes with the NodeJS distribution so [install NodeJS](https://nodejs.org/en/) from their site.

### Local Blockchain

Testing on Ethereum would be very expensive if you had to pay every time you had to update your code. To avoid this problem (and many others introduced by an asynchronous, global database) developers created local blockchains which you can spend all the Eth you want. The recommended choice is [Ganache](https://truffleframework.com/ganache), a GUI based Ethereum emulator.


## Machine Learning Tools

Most cutting edge machine learning is done using Python. Python is an easy to use but powerful programming language that has a large community and many Stack Overflow answers. In this section we will focus on how to use Python for ML.

### Get Python

The best way to get Python for machine learning is actually not to download it from their site. Rather use a Python package manager called Anaconda that does a lot of the hard work and nitty gritty of getting things to work. It also comes preinstalled with a lot of the packages that you will need, saving you a lot of time.

[Get Anaconda](https://www.anaconda.com/distribution/)

### Use Jupyter

After installing Anaconda, you can use a beautiful interactive "notebook" that can run code and hold notes. From your terminal run `jupyter notebook` to launch Jupyter. This is where you can rapidly prototype ideas using Python. For a longer tutorial on Jupyter, see [a general tutorial](https://plot.ly/python/ipython-notebook-tutorial/) or an [intro to Python with Jupyter](https://nbviewer.jupyter.org/urls/bitbucket.org/amjoconn/watpy-learning-to-code-with-python/raw/3441274a54c7ff6ff3e37285aafcbbd8cb4774f0/notebook/Learn%20to%20Code%20with%20Python.ipynb).

### Install Tensorflow and PyTorch

The most commonly used frameworks for machine learning are [PyTorch](https://pytorch.org/) and [Tensorflow](https://www.tensorflow.org/). We won't get into how to use them in this tutorial or even what they do but you can get a taste by following their tutorials:

- [PyTorch Tutorial](https://pytorch.org/tutorials/beginner/deep_learning_60min_blitz.html)
- [Tensorflow Tutorial](https://www.tensorflow.org/tutorials)


<div class="alert alert-block alert-info">
    <h5>Further Reading</h5>
    <ul>
        <li><a href="https://hackernoon.com/set-up-a-private-ethereum-blockchain-and-deploy-your-first-solidity-smart-contract-on-the-caa8334c343d">Creating your First Smart Contract</a></li>
        <li><a href="https://realpython.com/python-windows-machine-learning-setup/">Python Machine Learning Setup</a></li>
         <li><a href="https://www.scaler.com/topics/python/">Python Tutorials</a></li>
    </ul>
</div>
