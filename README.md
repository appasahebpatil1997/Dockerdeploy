# Dockerdeploy

pre-requisites for CentOS 7
ansible-galaxy collection install community.docker
curl -sSL https://bootstrap.pypa.io/get-pip.py -o get-pip.py
python get-pip.py
yum update for all the nodes
yum install epel-release
yum install ansible-------#cd /etc/ansible

to run the playbook
ansible-playbook {filename}.yml
