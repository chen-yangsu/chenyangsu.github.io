---
title: 'Anaconda3 installation for Windows Subsystem for Linux!'
date: 2020-06-25
permalink: /posts/2020/06/anaconda3-for-wsl/
tags:
  - anaconda3
---

Installing Anaconda3 on Ubuntu
======
1. Download Anaconda
- Go to [https://www.anaconda.com/products/individual](https://www.anaconda.com/products/individua)
- Copy the link address for Linux Python 3.7 64-Bit (x86) Installer
- Open Ubuntu and type ```cd .```  
- Then download Anaconda:    
```wget https://repo.anaconda.com/archive/Anaconda3-2020.02-Linux-x86_64.sh```
- Ensure (base) is not loaded by default  
```conda config --set auto_activate_base false```

2. Install Anaconda
- Execute the downloaded file  
```bash Anaconda3-2020.02-Linux-x86_64.sh```  
- **Note:** when following on-screen commands make sure to type ```yes``` after it asks  
```Do you wish the installer to initialize Anaconda3 by running conda init?```
- After installation, remove the installation file:  
```rm Anaconda3-2020.02-Linux-x86_64.sh```

3. Restart Ubuntu

For futher reference:   
- [Main Reference](https://danieltakeshi.github.io/2020/03/20/rlpyt/)
- [Other Reference](https://towardsdatascience.com/setting-up-a-data-science-environment-using-windows-subsystem-for-linux-wsl-c4b390803dd)
