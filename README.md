# Ansible playbook for user profile managment

The playbook to keep user profile for basic *nix applicaionons and make user profile preparation simple and sync across enviroements

### Dependencies 

The playbook uses the folowing role
[role_user_profile](https://github.com/zbitmanis/role_user_profile)

### How to use 
1. Install dependencies - the dependencies role will be saved within common_roles folder
``` ansible-galaxy install -r requirments.yml ```
2. Run the playbook - by default inventory hosts are pointing in the local host
``` ansible-playbook ansible-playbook profile.yml ```