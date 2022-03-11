# dev-vagrant
Building a virtual environment with Vagrant and creating a new user using Ansible

$ vagrant init hashicorp/bionic64 \
$ vagrant up 

Vagrantfile set to the IP 192.168.33.10 \

Commands for the Ansible \ 
$ ansible-playbook -i vagrant_inventory create_user.yaml -vvv 
$ ssh -i ~/.ssh/id_rsa newvagrantuser@192.168.33.10
