Role Name
=========
[learning]
This role is used for installation of basic apache server on the ubuntu managed nodes .

Requirements
------------

1. Ansible Environment Requirements
2.Create an inventory file (e.g., inventory.ini) that lists the Ubuntu servers where Apache will be installed. 
3. Target Host Requirements
Operating System
Ensure that the target hosts are running a supported version of Ubuntu (e.g., 18.04, 20.04, or 22.04).
Package Updates

4. Playbook Configuration
Create a playbook file (e.g., apache_install.yml) to use the selected role. Here’s an example:

5. Network Requirements
Ensure that the target Ubuntu servers have:

6.An accessible IP address.
Open ports for HTTP (80) and HTTPS (443) in their firewall settings. You can use ufw (Uncomplicated Firewall) to manage this:
bash
Copy code
sudo ufw allow 'Apache Full'
8. Running the Playbook

Role Variables
--------------

A description of the settable variables for this role should go here, including any variables that are in defaults/main.yml, vars/main.yml, and any variables that can/should be set via parameters to the role. Any variables that are read from other roles and/or the global scope (ie. hostvars, group vars, etc.) should be mentioned here as well.
