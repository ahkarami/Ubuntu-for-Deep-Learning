# Some Other Notes & Examples of Ubuntu Commands (Part1):


## Kill Process:
The common syntax for _kill_ command is:  
`# kill [signal or option] PID(s)`  
In order to know more about _Signal names_ refer to [1](https://www.tecmint.com/how-to-kill-a-process-in-linux/).  

- Example1:  
`kill -15 3139` --> The command will kill the process having **pid=3139**, where **PID** is a **Numerical Value** of process.

- Example2:  
To know all the processes and correspondingly their assigned **pid**, run:
`# ps -A`

- Example3:  
Know the **PID** of exact process (_e.g.,_ mysqld):
`# pidof mysqld` 


## Shutdown Commands in Ubuntu:
- [Understanding Shutdown, Poweroff, Halt and Reboot Commands in Linux](https://www.tecmint.com/shutdown-poweroff-halt-and-reboot-commands-in-linux/)
- Example1:  
`shutdown 13:20` --> This command will shutdown your computer at 13:20'.

## Find Last Shutdown time in ubuntu:
- `last -x|grep shutdown | head -1`
- [Linux Find Out Last System Reboot Time and Date Command](https://www.cyberciti.biz/tips/linux-last-reboot-time-and-date-find-out.html)  

## GPU Process Monitoring in Ubuntu:
- `watch -n0.1 nvidia-smi` --> Where 0.1 is the time interval, in seconds.  
- [NVTOP - NVidia TOP](https://github.com/Syllo/nvtop)  

## Disable Sleep in Ubuntu:
- [Disable Sleep in Ubuntu - Link1](https://www.unixtutorial.org/disable-sleep-on-ubuntu-server/)  
- [Disable Sleep in Ubuntu - Link2](https://askubuntu.com/questions/47311/how-do-i-disable-my-system-from-going-to-sleep)  

## Install `Tex` in Ubuntu:
- type `sudo apt-get install texlive`
- type `sudo apt-get install texstudio`

- Refrence: [Installing LaTeX on Ubuntu](https://dzone.com/articles/installing-latex-ubuntu)

## Some Notes about Terminal in Ubuntu:
- [A Gentle Introduction to tmux](https://hackernoon.com/a-gentle-introduction-to-tmux-8d784c404340)
- [An Introduction to the Linux Terminal](https://www.digitalocean.com/community/tutorials/an-introduction-to-the-linux-terminal)  

### Beautiful Terminal in Ubuntu:
- [How you can style your terminal like Medium, freeCodeCamp, or any way you want](https://medium.freecodecamp.org/how-you-can-style-your-terminal-like-medium-freecodecamp-or-any-way-you-want-f499234d48bc)
- [Install Z-shell (Oh My Zsh) on Ubuntu 18.04 LTS](https://dev.to/mskian/install-z-shell-oh-my-zsh-on-ubuntu-1804-lts-4cm4)  
- [Oh-My-Zsh!](https://medium.com/wearetheledger/oh-my-zsh-made-for-cli-lovers-installation-guide-3131ca5491fb)  
- [How to Setup ZSH and Oh-my-zsh on Linux](https://www.howtoforge.com/tutorial/how-to-setup-zsh-and-oh-my-zsh-on-linux/)  

## How to Install Ubuntu Alongside With Windows:
- [How to Install Ubuntu 16.10/16.04 Alongside With Windows 10 or 8 in Dual-Boot](https://www.tecmint.com/install-ubuntu-16-04-alongside-with-windows-10-or-8-in-dual-boot/)  [_Good_]
- [Installing Ubuntu 18.04 along with Windows 10 (Dual Boot Installation) for Deep Learning](https://hackernoon.com/installing-ubuntu-18-04-along-with-windows-10-dual-boot-installation-for-deep-learning-f4cd91b58557)  
- [20 Things To Do After Installing Ubuntu](https://www.tecmint.com/things-to-do-after-installing-ubuntu/)  
- [Most Popular Download Managers for Linux](https://www.tecmint.com/download-managers-for-linux/)  [_I use KGet_]  

## Upgrade Ubuntu 18.04 To Ubuntu 20.04:
- [2 Ways to Upgrade Ubuntu 18.04 To Ubuntu 20.04 (Graphical & Terminal)](https://www.linuxbabe.com/ubuntu/upgrade-ubuntu-18-04-to-ubuntu-20-04)  
- [Error `symbol-grub-file-filters` for upgrading ubuntu18.04 to 20.04](https://askubuntu.com/questions/1267970/error-symbol-grub-file-filters-not-found-upgrade-ubuntu18-04-to-20-04)    

## Upgrade Ubuntu Packages:
- [Upgrading Ubuntu Packages via Command Line](https://tecadmin.net/upgrading-ubuntu-packages-command-line/)  
- [Update Ubuntu 20.04 Packages](https://linuxconfig.org/how-to-update-ubuntu-packages-on-ubuntu-20-04-focal-fossa-linux)  

## Simple Ways To Free Up Space on Ubuntu:
- [5 Simple Ways To Free Up Space on Ubuntu](https://www.omgubuntu.co.uk/2016/08/5-ways-free-up-space-on-ubuntu)  
- [5 Best Ways to Free up Hard Disk Space in Ubuntu](https://www.fosslinux.com/2986/free-up-hard-disk-space-ubuntu.htm)  

## Install Nvidia Drivers in Ubuntu:
- [How to Install Nvidia Drivers in Ubuntu](https://www.tecmint.com/install-nvidia-drivers-on-ubuntu/)
- [Install NVIDIA Driver and CUDA on Ubuntu](https://gist.github.com/wangruohui/df039f0dc434d6486f5d4d098aa52d07)  

## Remove CUDA:
- [Removing Nvidia CUDA Toolkit](https://askubuntu.com/questions/530043/removing-nvidia-cuda-toolkit-and-installing-new-one)  
- [How to Remove cuda Completely from Ubuntu](https://stackoverflow.com/questions/56431461/how-to-remove-cuda-completely-from-ubuntu)  

## Some Notes about Python:
- [Python, argparse, and command line arguments](https://www.pyimagesearch.com/2018/03/12/python-argparse-command-line-arguments/) [**Very Important**]
- [Tools to run Python on Android](https://medium.com/@umerfarooq_26378/tools-to-run-python-on-android-9060663972b4) [_Very Interesting_]
- [Data Science Skills: Web scraping using python (**Web Crawling**)](https://towardsdatascience.com/data-science-skills-web-scraping-using-python-d1a85ef607ed)
- [An A-Z of useful Python tricks](https://medium.freecodecamp.org/an-a-z-of-useful-python-tricks-b467524ee747)
- [Python Tricks 101](https://hackernoon.com/python-tricks-101-2836251922e0)
- [Essential ML Cheat Sheets](https://startupsventurecapital.com/essential-cheat-sheets-for-machine-learning-and-deep-learning-researchers-efb6a8ebd2e5) [_Very Important & Useful_]
- [Cheat Sheets AI](https://github.com/kailashahirwar/cheatsheets-ai) [_Very Important & Useful_]
- [How to Generate a Word Cloud of Any Shape in Python](https://blog.goodaudience.com/how-to-generate-a-word-cloud-of-any-shape-in-python-7bce27a55f6e)
- [Create your own API from Websites](https://medium.com/@mottet.dev/scrapy-and-scrapyrt-how-to-create-your-own-api-from-almost-any-website-ecfb0058ad64)
- [How to Run Parallel Data Analysis in Python using Dask Dataframes](https://towardsdatascience.com/trying-out-dask-dataframes-in-python-for-fast-data-analysis-in-parallel-aa960c18a915)
- [9 Things You Should Know About TensorFlow](https://hackernoon.com/9-things-you-should-know-about-tensorflow-9cf0a05e4995)
- [Automatic Image Quality Assessment in Python](https://medium.com/@r.ocampo.vega/automatic-image-quality-assessment-in-python-391a6be52c11)
- [Extracting colours from an image using k-means clustering](https://towardsdatascience.com/extracting-colours-from-an-image-using-k-means-clustering-9616348712be)
- [An Introduction to Text Summarization using the TextRank Algorithm (with Python implementation)](https://medium.com/analytics-vidhya/an-introduction-to-text-summarization-using-the-textrank-algorithm-with-python-implementation-2370c39d0c60)
- [Batch and Streaming in the World of Data Science and Data Engineering](https://medium.com/capital-one-tech/batch-and-streaming-in-the-world-of-data-science-and-data-engineering-2cc029cdf554)
- [Working With JSON Data in Python](https://realpython.com/python-json/)
- [Duplicate Image Finder](https://github.com/philipbl/duplicate-images) [_Useful Repository_]
- [How to build an image duplicate finder for your dataset](https://towardsdatascience.com/how-to-build-an-image-duplicate-finder-f8714ddca9d2) [_Useful Repository_]
- [Fast, optimized ‘for’ pixel loops with OpenCV and Python](https://www.pyimagesearch.com/2017/08/28/fast-optimized-for-pixel-loops-with-opencv-and-python/) [_Useful_]
- [How to build blazing fast REST APIs with Node.js, MongoDB, Fastify and Swagger](https://medium.freecodecamp.org/how-to-build-blazing-fast-rest-apis-with-node-js-mongodb-fastify-and-swagger-114e062db0c9) [_Semi Good_]
- [Why is Python so slow?](https://hackernoon.com/why-is-python-so-slow-e5074b6fe55b)  

## Configuring Ubuntu for Deep Learning Code Developers:
- [Configuring Ubuntu for deep learning with Python](https://www.pyimagesearch.com/2017/09/25/configuring-ubuntu-for-deep-learning-with-python/)
- [The perfect computer vision environment: PyCharm, OpenCV, and Python virtual environments](https://www.pyimagesearch.com/2015/08/17/the-perfect-computer-vision-environment-pycharm-opencv-and-python-virtual-environments/)
- [Ubuntu with Virtual Machine for Deep Learning Code Developers (with Python)](https://www.pyimagesearch.com/2017/09/22/deep-learning-python-ubuntu-virtual-machine/)
- [How to install OpenCV 4 on Ubuntu](https://www.pyimagesearch.com/2018/08/15/how-to-install-opencv-4-on-ubuntu/)
- [Setting up Ubuntu 16.04 + CUDA + GPU for deep learning with Python](https://www.pyimagesearch.com/2017/09/27/setting-up-ubuntu-16-04-cuda-gpu-for-deep-learning-with-python/)
- [Workstation-installation](https://github.com/moabitcoin/ml-village/blob/master/Workstation-installation.md)  

## Setup OpenCV for Android:
- [A Beginner’s Guide to Setting up OpenCV Android Library on Android Studio](https://android.jlelse.eu/a-beginners-guide-to-setting-up-opencv-android-library-on-android-studio-19794e220f3c)

## Play `.wma` files in ubuntu 18:
- `sudo apt install gstreamer1.0-plugins-ugly`
- [Reference: Is there a free option for playing WMA files?](https://askubuntu.com/questions/38091/is-there-a-free-option-for-playing-wma-files)  

## Ubuntu Screenshots and screen casts:
- `Shift+Prt Scrn` to take a screenshot of an area you select.  
- The image is automatically saved in your `Pictures` folder in your `home` folder with a file name that begins with Screenshot and includes the date and time it was taken.  
- [Reference](https://help.ubuntu.com/stable/ubuntu-help/screen-shot-record.html)  

## Manipulating rar Files in Ubuntu:
- [How to Open, Extract, and Create rar Files in Linux](https://www.tecmint.com/how-to-open-extract-and-create-rar-files-in-linux/)  

## VNC Connect - is a screen sharing software [_e.g._, for Ubuntu Servers]:  
- [VNC Connect](https://www.realvnc.com/en/connect/download/vnc/linux/)  

## Download a large file from Google Drive (via Ubuntu CLI or Python):
- [gdown - Download a large file from Google Drive](https://pypi.org/project/gdown/)  [_Great_]  
- [gdown - Download Google Drive files from CLI or Python](https://github.com/wkentaro/gdown) [_Great_]    

## Upload files from Ubuntu CLI:
- [File Sharing from Linux Command Line](https://www.tecmint.com/file-sharing-from-linux-commandline/) [**Great**]  


