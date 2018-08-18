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

## Install `Tex` in Ubuntu:
- type `sudo apt-get install texlive`
- type `sudo apt-get install texstudio`

- Refrence: [Installing LaTeX on Ubuntu](https://dzone.com/articles/installing-latex-ubuntu)

## Configuring Ubuntu for Deep Learning Code Developers:
- [Configuring Ubuntu for deep learning with Python](https://www.pyimagesearch.com/2017/09/25/configuring-ubuntu-for-deep-learning-with-python/)
- [The perfect computer vision environment: PyCharm, OpenCV, and Python virtual environments](https://www.pyimagesearch.com/2015/08/17/the-perfect-computer-vision-environment-pycharm-opencv-and-python-virtual-environments/)
- [Ubuntu with Virtual Machine for Deep Learning Code Developers (with Python)](https://www.pyimagesearch.com/2017/09/22/deep-learning-python-ubuntu-virtual-machine/)

