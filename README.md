# Ancible-Ec2
The Ansible-Ec2 repository is a good starting point for using ansible in aws ec2.


## Install Python
http://bicofino.io/2014/01/16/installing-python-2-dot-7-6-on-centos-6-dot-5/

## Install Ansible

## Configure EC2

ansible all --list-hosts
Copy public DNS from AWS console to ansible hosts file - Location /etc/ansible/hosts

#### Setup Hosts File
sudo vim /etc/hosts
[aws]
DNS name
ctrl+c :wq

#### Create Playbook

#### Rnu Playbookm
ssh-agen bash
copy the pem file to the play book folder
cp ../*pem .
ssh-add pemkey filename
ansible-playbook playbookname.yml





