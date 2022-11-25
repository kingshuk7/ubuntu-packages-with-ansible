# Ansible Playbook for Installing Packages in Local Ubunutu Machine
This `Ansible` playbook installs your desired packages to local Ubuntu machine

## CLI Usage
Clone the repository, modify the packages name in the file `/playbooks/install_package.yaml` accoding to your requirement and run the ```ansible-playbook``` as mentioned below.
```bash
cd ~/
git clone https://github.com/kinghub007/ubuntu-packages-with-ansible.git
cd ubuntu-packages-with-ansible
sudo ansible-playbook playbooks/install_package.yaml
```

## Requirement
1. `Ansible` needs to be installed on the machine. For installing `Ansible` run the below-mentioned command.
```bash
sudo apt-get install ansible
```
2. `Python` needs to be installed on the client. For installing `Python`crun the below-mentioned command.
```bash
ansible <remote_host> -u <remote_user> -m raw -a "sudo apt-get install python"
```
## FYI
The remote_user needs to have `sudo` privilege.
