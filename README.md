# local-k8s
Local k8s cluster(s) for development purposes; Vagrant + Ansible

The Vagrantfile and main ansible-playbook  will be build a three node cluster with one control-plane node, and nodes will run Debian 10. Each node is given a static IP and set configured into a cluster through the use of 4 different ansible-galaxy roles. 

references: 
- https://www.linuxscrew.com/install-pip
