## Raspberry Pi Setup
### OS and Kubernetes
Ubuntu 20.04 + K3s

### Networking

### SSH


## Install K3s

### K3s Ansible Playbook
sudo apt install python3-pip
pip3 install ansible --user

Clone the k3s-ansible repo

### Configure kubectl
 ansible-playbook site.yml -i inventory/rpi/hosts.ini


