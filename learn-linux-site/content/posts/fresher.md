---
title: "Setup Tools"
date: 2021-07-29T15:44:07+05:30
draft: false
---

# Installation guide

A guide to help you through the basic installation for ubuntu!
Brave installation:

```
sudo snap install brave
```

Joplin installation:

```
sudo apt update
sudo apt install snapd
sudo snap install joplin-desktop
```
Docker:
```
sudo apt install docker.io
```
Type in the following to verify if docker has been installed:
```
sudo docker
```
Postman:
```
sudo snap install postman
```
Apt installation:
```
sudo apt update
sudo apt install snapd
```
Install Visual Studio Code:
```
sudo snap install --classic code
```
Install zoom:
```
sudo snap install zoom-client
```
Install slack:
```
sudo snap install slack --classic
```
Install git:
```
sudo apt install git
```
Add ssh:
```
ssh-keygen -t rsa -b 4096 -C "youremail@gmail.com"
eval "$(ssh-agent -s)"
ssh-add ~/.ssh/id_rsa
cat ~/.ssh/id_rsa.pub
```
Once you're done with the above commands, copy the SSH key generated and add it in GitHub.

To do so, go to settings on GitHub, then you will find SSH and GPG keys on the left hand side panel. Go into it and add in the SSH key generated and name it.

Mini conda installation:
```
cd /tmp
wget https://repo.anaconda.com/miniconda/Miniconda3-latest-Linux-x86_64.sh
chmod +x Miniconda3-latest-Linux-x86_64.sh
./Miniconda3-latest-Linux-x86_64.sh
```
Once you're done with the above steps, close the terminal and open it again. Then type in the following command:
```
conda config --set auto_activate_base false
```
To create a new environment, follow the command below:
```
conda create -n py38 -y python=3.8
```
To activate and deactivate the environment, type in the commands below:
```
conda activate py38
conda deactivate
```
