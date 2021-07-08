# local-k8s
Local k8s cluster(s) for development purposes; Vagrant + Ansible

The Vagrantfile and main ansible-playbook  will be build a three node cluster with one control-plane node, and nodes will run Debian 10. Each node is given a static IP and set configured into a cluster through the use of 4 different ansible-galaxy roles. 
---
Task: Use Ansible to copy a directory from your host machine to a running virtualbox machine (kube1 in this example).

`ansible kube1 -m copy "src=~/repos/local-k8s/keycloak dest=~"`

  - `-m copy` - using the copy module

references: 
- https://www.linuxscrew.com/install-pip
- https://blog.alexellis.io/ingress-for-your-local-kubernetes-cluster/ --- inlets for your local cluster
