# Setup Centos 7 for use with Python3, Ansible, and Netmiko

Instructions:

```
sudo yum install ansible git -y
git clone https://github.com/Pluppo/ansible-centos-setup.git
ansible-playbook ansible-centos-setup/centos.yml -K
```
