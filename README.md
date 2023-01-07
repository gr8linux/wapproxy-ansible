# wapproxy-ansible
Ansible file to prepare and deploy the whatsapp docker-compose on a virtual machine

To run this play book you just need to install ansible on your desktop and run the below command

## Install ansible on Ubuntu
You could install ansible by the apt command 
```bash
apt update
apt install ansible
```

Or by the pip command
```bash
apt install python3-pip
```
```bash
pip3 install ansible
```
## Clone the repo
```bash
git clone https://www.github.com/gr8linux/wapproxy-anible.git
cd wapproxy-ansible
```
## Run deploy the proxy on a vm
```bash
ansible-playbook -i YOURINVENTORY -u root dockery.yml
```
