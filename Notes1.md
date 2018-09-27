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

## Install `Tex` in Ubuntu:
- type `sudo apt-get install texlive`
- type `sudo apt-get install texstudio`

- Refrence: [Installing LaTeX on Ubuntu](https://dzone.com/articles/installing-latex-ubuntu)

## Some Notes about Terminal in Ubuntu:
- [How you can style your terminal like Medium, freeCodeCamp, or any way you want](https://medium.freecodecamp.org/how-you-can-style-your-terminal-like-medium-freecodecamp-or-any-way-you-want-f499234d48bc)
- [A Gentle Introduction to tmux](https://hackernoon.com/a-gentle-introduction-to-tmux-8d784c404340)

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
- [Why is Python so slow?](https://hackernoon.com/why-is-python-so-slow-e5074b6fe55b)  

## Configuring Ubuntu for Deep Learning Code Developers:
- [Configuring Ubuntu for deep learning with Python](https://www.pyimagesearch.com/2017/09/25/configuring-ubuntu-for-deep-learning-with-python/)
- [The perfect computer vision environment: PyCharm, OpenCV, and Python virtual environments](https://www.pyimagesearch.com/2015/08/17/the-perfect-computer-vision-environment-pycharm-opencv-and-python-virtual-environments/)
- [Ubuntu with Virtual Machine for Deep Learning Code Developers (with Python)](https://www.pyimagesearch.com/2017/09/22/deep-learning-python-ubuntu-virtual-machine/)
- [Setting up Ubuntu 16.04 + CUDA + GPU for deep learning with Python](https://www.pyimagesearch.com/2017/09/27/setting-up-ubuntu-16-04-cuda-gpu-for-deep-learning-with-python/)

## Setup OpenCV for Android:
- [A Beginner’s Guide to Setting up OpenCV Android Library on Android Studio](https://android.jlelse.eu/a-beginners-guide-to-setting-up-opencv-android-library-on-android-studio-19794e220f3c)

