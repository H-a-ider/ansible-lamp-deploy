# ansible-lamp-deploy

To use this Ansible playbook to deploy a LAMP stack on your target Linux servers, follow these steps:

(1) Navigate to the playbook directory:

cd ansible-lamp-deploy

(2) Update the inventory file (inventory.ini) with the IP addresses or hostnames of your target Linux servers and any additional configuration variables.

(3) Run the Ansible playbook with the following command:

ansible-playbook -i /path/to/inventory.ini lamp.yml -K

Replace /path/to/inventory.ini with the path to your updated inventory file.

The -K flag prompts for the sudo (root) password if necessary.
