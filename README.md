# ansible_mbp_fedora_25
Help configure macbook pro for Fedora 25.

Install Ansible:
```bash
sudo yum install -y epel-release
sudo yum install -y python-pip
sudo yum install -y python-devel
sudo yum group install -y "Development Tools"
sudo yum install -y openssl-devel
sudo yum install -y vim-enhanced
sudo yum install -y libffi-devel
sudo pip install --upgrade pip
sudo pip install virtualenv

cd ~
mkdir ansible
cd ansible
virtualenv venv
source ./venv/bin/activate
pip install ansible
```
