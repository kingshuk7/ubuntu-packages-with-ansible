# Ansible Playbook for Installing Packages in Local Ubunutu Machine
This ```Ansible``` playbook installs your desired packages to local Ubuntu machine

## CLI Usage
Clone the repository, modify the packages name in the file ```/playbooks/install_package.yaml``` accoding to your requirement and run the ```ansible-playbook``` as mentioned below.
```bash
cd ~/
git clone https://github.com/kinghub007/ubuntu-packages-with-ansible.git
cd ubuntu-packages-with-ansible
ansible-playbook playbooks/install_package.yaml
```

## Requirement
```Ansible``` needs to be installed on the machine. For installing ```Ansible``` run the below-mentioned command.
```bash
sudo apt-get install ansible
```
