# Ancible-Ec2
The Ansible-Ec2 repository is a good starting point for using ansible in aws ec2.


## Install Python

## Install Ansible

## Configure EC2

ansible all --list-hosts
Copy public DNS from AWS console to ansible hosts file - Location /etc/ansible/hosts


Setup SSH for EC2 :
ssh-agen bash
copy the pem file to the play book folder
cp ../*pem .
ssh-add pemkey filename


sudo vim /etc/hosts
[aws]
DNS name

ctrl+c :wq
Create Playbook
Run Palybook  - ansible-playbook playbookname.yml
