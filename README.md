apt update && apt upgrade -y
apt install -y ansible
/etc/ansible/hosts/
platform.ini 
ansible all -i platform.ini -m ping
/etc/ansible/playbook
playbook.yml




