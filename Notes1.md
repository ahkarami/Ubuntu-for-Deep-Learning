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


