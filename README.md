Setup Centos 7 for use with Python3, Ansible, and Netmiko

Instructions:

1. Install Ansible and git:
sudo yum install ansible wget -y

2. Clone repo:
git clone https://github.com/Pluppo/ansible-centos-setup.git

3. Run playbook:
sudo ansible-playbook ansible-centos-setup/centos.yml
