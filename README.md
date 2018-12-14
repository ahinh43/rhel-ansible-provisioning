# rhel-ansible-provisioning
This playbook installs a few packages, registers the system to Redhat and adds ahinh_admin as an administrator user.
Placed here for reference.

# What is not included:
Flag --ask-become-pass is passed into the command every time the command is run. An account named ansible_admin is needed and the server will need the public key for the admin account to be in the remote server before running playbook.
