# Openstack-Newton-Installation



1. Clone the Repository 
2. change the variables according to your environment in "group_vars/all" file 
3. Run the installer.yml 
   
   ansible-playbook  installer.yml --extra-vars "ansible_sudo_pass='$sudo Password' "
