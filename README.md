# Ubuntu-for-Deep-Learning
Useful notes about Ubuntu (especially for **Deep Learning** code developers)

![Logo](./FinalLogo.jpg)

## General useful links:
- [Beginner's Guide for linux](https://www.tecmint.com/free-online-linux-learning-guide-for-beginners/)
- [Linux tricks](https://www.tecmint.com/tag/linux-tricks/)

## Other important & useful links:
- [25 Useful Basic Commands of `apt-get` for Package Management](https://www.tecmint.com/useful-basic-commands-of-apt-get-and-apt-cache-for-package-management/)
- [How To Install `pip` to Manage Python Packages in Linux](https://www.tecmint.com/install-pip-in-linux/)
- [How to Install Latest _Python 3.6_ Version in Linux](https://www.tecmint.com/install-python-in-linux/)
- [20 Command Line Tools to Monitor Linux Performance](https://www.tecmint.com/command-line-tools-to-monitor-linux-performance/)

## Install deep learning packages:

### Install PyTorch 0.3.1 (for python 3.5 & CUDA 9.0):
- Type `sudo su` in ubuntu terminal
- After inserting your ubuntu's password, then type `pip3 install --upgrade http://download.pytorch.org/whl/cu90/torch-0.3.1-cp35-cp35m-linux_x86_64.whl`
- Type `pip3 install --upgrade torchvision`

### Install TensorFlow 1.7 GPU based (for python 3.5 & CUDA 9.0):
- First download its `whl` file via the below command:
- ```wget https://files.pythonhosted.org/packages/e3/e8/9496b0663fef0415094a598deb1099aaa2a69f2bc9d924cafd05677d3c85/tensorflow_gpu-1.7.0-cp35-cp35m-manylinux1_x86_64.whl```
- Then type `sudo su` in ubuntu terminal
- After inserting your ubuntu's password, then type `pip3 install --upgrade YourDownloadedAddress/tensorflow_gpu-1.7.0-cp35-cp35m-manylinux1_x86_64.whl`
- **Note** that in the above command the `YourDownloadedAddress` is the address of `whl` file (_e.g.,_ `/home/smith/Programs`) 


## Install required packages:

### Install `pip3` on ubuntu:
- Type `sudo apt-get update`
- Type `sudo su` in ubuntu terminal
- After inserting your ubuntu's password, then type `apt install python3-pip`
- After install _pip3_ then upgrade it via the below command:
- `pip3 install --upgrade setuptools pip`

### Install opencv-python:
- Type `sudo su` in ubuntu terminal
- After inserting your ubuntu's password, then type `pip3 install --upgrade opencv-python`  

### Install h5py:
- Type `sudo su` in ubuntu terminal
- After inserting your ubuntu's password, then type `pip3 install --upgrade h5py`  
