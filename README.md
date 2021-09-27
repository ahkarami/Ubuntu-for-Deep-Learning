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
- [Check CUDA and cuDNN version](https://medium.com/@changrongko/nv-how-to-check-cuda-and-cudnn-version-e05aa21daf6c)
- [Add “New Document” back to the right-click menu in Ubuntu 18.04](https://vitux.com/add-new-document-back-to-the-right-click-menu-in-ubuntu-18-04/)  

### Package Management Notes in Ubuntu:
- [3 Command Line Tools to Install Local Debian (.DEB) Packages](https://www.tecmint.com/install-local-deb-packages-in-debian-ubuntu-linux-mint/)
- [15 Practical Examples of `dpkg commands` for Debian Based Distros](https://www.tecmint.com/dpkg-command-examples/)
- [General notes about Package Management in Ubuntu](https://help.ubuntu.com/lts/serverguide/package-management.html.en)
- [dpkg](https://help.ubuntu.com/lts/serverguide/dpkg.html.en)
- [Apt](https://help.ubuntu.com/lts/serverguide/apt.html.en)

### Python Virtual Environments:
- [Python Virtual Environments](https://realpython.com/python-virtual-environments-a-primer/)

### Managing Python Version Dependencies:
- [Managing Dependencies in Python](https://tech.instacart.com/freezing-pythons-dependency-hell-in-2018-f1076d625241)

### Docker:
- [Learn more about how to install docker](https://github.com/Microsoft/MMdnn/blob/master/docs/InstallDockerCE.md) [_Install Docker Community Edition(CE)_]

### Set & Change DNS on Ubuntu Server:
- [How to set DNS nameservers on Ubuntu](https://linuxize.com/post/how-to-set-dns-nameservers-on-ubuntu-18-04/)   
- [Ubuntu DNS nameservers](https://phoenixnap.com/kb/ubuntu-dns-nameservers)   

## Install deep learning packages:

### Install PyTorch 0.3.1 (for python 3.5 & CUDA 9.0):
- Type `sudo su` in ubuntu terminal
- After inserting your ubuntu's password, then type `pip3 install --upgrade http://download.pytorch.org/whl/cu90/torch-0.3.1-cp35-cp35m-linux_x86_64.whl`
- Type `pip3 install --upgrade torchvision`

### Install TensorFlow 1.7 GPU based (for python 3.5 & CUDA 9.0 & cuDNN 7.0.5):
- First download its `whl` file via the below command:
- ```wget https://files.pythonhosted.org/packages/e3/e8/9496b0663fef0415094a598deb1099aaa2a69f2bc9d924cafd05677d3c85/tensorflow_gpu-1.7.0-cp35-cp35m-manylinux1_x86_64.whl```
- Then type `sudo su` in ubuntu terminal
- After inserting your ubuntu's password, then type `pip3 install --upgrade YourDownloadedAddress/tensorflow_gpu-1.7.0-cp35-cp35m-manylinux1_x86_64.whl`
- **Note** that in the above command the `YourDownloadedAddress` is the address of `whl` file (_e.g.,_ `/home/smith/Programs`) 

### Install MXNet 1.2.0 (for python 3.5 & CUDA 9.0):
- Type `sudo su` in ubuntu terminal
- After inserting your ubuntu's password, then type `pip3 install --upgrade mxnet-cu90 --pre`

### Install Keras 2.2.0 (for python 3.5 & CUDA 9.0 & cuDNN 7.0.5 & TensorFlow Backend):
- Type `sudo su` in ubuntu terminal
- After inserting your ubuntu's password, then type `pip3 install --upgrade keras`

### Install 2 Different Versions of a package (_e.g.,_ PyTorch) on a Single System:
Suppose one wants to install 2 different versions of a deep learning package (_e.g.,_ PyTorch) on a single system. We assume that the _PyTorch 0.3.1_ has been installed via _pip3_. Now we want to install _PyTorch 0.4.0_ (_i.e.,_ we want to have both versions on a signle system). To this end, follow below instructions:
- 1- `sudo mkdir /opt/pytorch4`
- 2- `sudo chown -R username:username /opt/pytorch4` (**Note:** instead of `username` you must type your username (_e.g.,_ smith))
- 3- Download the _*.whl_ file of _PyTorch 0.4.0_ from its [Pip3 Repository](http://download.pytorch.org/whl/cu90/torch-0.4.0-cp35-cp35m-linux_x86_64.whl)
- 4- Extract it
- 5- Copy all of the extracted files into "/opt/pytorch4"
- 6- When run Python3 the type:
```python
import sys
sys.path.insert(0, "/opt/pytorch4/")
import torch
print(torch.__version__) 
```
- 7- **Note:** If you don't type the above commands, then the default version of PyTorch (_i.e.,_ the previous installed it via pip3 (0.3.1 version)) is worked.


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

### Install opencv-contrib-python:
- Type `sudo su` in ubuntu terminal
- After inserting your ubuntu's password, then type `pip3 install --upgrade opencv-contrib-python`

### Install [Dlib](https://github.com/davisking/dlib):
- `sudo apt-get install build-essential cmake`
- `sudo apt-get install libgtk-3-dev`
- `sudo apt-get install libboost-all-dev`
- `sudo su`
- `pip3 install dlib`

### Install Pillow:
- Type `sudo su` in ubuntu terminal
- After inserting your ubuntu's password, then type `pip3 install --upgrade Pillow`

### Install scikit-learn:
- Type `sudo su` in ubuntu terminal
- After inserting your ubuntu's password, then type `pip3 install --upgrade -U scikit-learn`  

### Install h5py:
- Type `sudo su` in ubuntu terminal
- After inserting your ubuntu's password, then type `pip3 install --upgrade h5py`  

### Install Jupyter Notebook:
- Type `sudo su` in ubuntu terminal
- After inserting your ubuntu's password, then type `pip3 install --upgrade jupyter`  

### Install OpenCV in Ubuntu for C++:
- [How to Install OpenCV in Ubuntu 16.04 LTS for C / C++](http://www.codebind.com/cpp-tutorial/install-opencv-ubuntu-cpp/)
- [Ubuntu 16.04: How to install OpenCV](https://www.pyimagesearch.com/2016/10/24/ubuntu-16-04-how-to-install-opencv/)
- [How to install OpenCV 4 on Ubuntu](https://www.pyimagesearch.com/2018/08/15/how-to-install-opencv-4-on-ubuntu/)  

## Other Useful Notes:

### Open New Terminal:
- `Ctrl + Alt + T` that opened a terminal window.
- `Ctrl + Shift + T` that opened a new tab in a terminal.

### Show the CUDA Installed version:
- `sudo apt show cuda`

### Show the CuDNN Installed version:
- `apt search cudnn`

