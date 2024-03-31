# You need to set ANSIBLE_CONFIG=/path/to/ansible.cfg
# Provide your .ssh/config file to use the hosts there.
#    [ssh_connection]
#    ssh_args = -F '/Users/zach/.ssh/config'
#
# https://docs.ansible.com/ansible/latest/installation_guide/intro_configuration.html

up:
	ansible-playbook ubuntu-22.yml -i inv-file.yml --verbose

down:
	echo "down"

check:
	ansible-playbook -i inv-file.yml --check ubuntu-22.yml

.PHONY: up down check