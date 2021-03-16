[![GitHub stars](https://img.shields.io/github/stars/Th3SnowyOwl/Gitpod-VNC?label=Stars&style=plastic)](https://github.com/Th3SnowyOwl/Gitpod-VNC/stargazers)  
[![GitHub license](https://img.shields.io/github/license/Th3SnowyOwl/Gitpod-VNC)](https://github.com/Th3SnowyOwl/Gitpod-VNC)  
# Gitpod-VNC  
This is a repository for running "novnc" inside of gitpod, just use the prefix on this repository, or just click this link   
# Creating Accounts  
First, make sure you have a [github](https://github.com/join?ref_cta=Sign+up&ref_loc=header+logged+out&ref_page=%2F&source=header-home) account for syncing with gitpod.  
Then, Create a [Gitpod.io](https://gitpod.io/login/) account to set up your workspace.  
# Feature Preview  
Once logged in, navagate to [Gitpod account settings](https://gitpod.io/settings/), and enable feature preview. Which enables sudo in gitpod, which is essential for installing our packages and updating our workspace.  
![You need internet clown](https://raw.githubusercontent.com/Th3SnowyOwl/Gitpod-VNC/master/image.png)  
# Starting Your Workspace
[https://gitpod.io/#https://github.com/Th3SnowyOwl/Gitpod-VNC](https://gitpod.io/#https://github.com/Th3SnowyOwl/Gitpod-VNC)  
Then run this command in terminal once the port 6080 pops up.  
**Please remember, gitpod will not save installed packages or any command you run, it only forks the current github repository, (ie here) so you have to run the command every time.**  
```bash
sudo apt update && sudo apt upgrade -y && sudo apt install firefox -y && firefox
```  
# Disclaimer
Please keep in mind gitpod.io's rules, I am not responsible for you crashing thier servers.  
These vnc's have no gpu, so any gui's will be slow to load, don't try playing youtube videos, they suck because the cpu has to render everything pixel by pixel. 
