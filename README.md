# Bash-Shell-Scripting-Intro-

A very basic bash scripting commands only for my reference

---

#### Updating the Ubuntu

Entering nano and then saving it with update file name

    #!/bin/bash
    sudo apt update
    sudo apt-dist upgrade
    exit

#### How to run it?

    ls
    chmod +x update
    ./update
    
---

#### Checking our System

    #!/bin/bash
    echo "Memory:"
    free -h
    echo "Disk Usage:"
    du -h
    echo "Uptime:"
    uptime
    exit

Created a bin folder in directory and named my nano file as sys-check.
Following command will make the bash script unreplacable.

    mv sys-check ~/bin/

![image](https://user-images.githubusercontent.com/66274690/184526511-0c7a63d5-52e5-44e5-a6b8-eded872f1524.png)

---
