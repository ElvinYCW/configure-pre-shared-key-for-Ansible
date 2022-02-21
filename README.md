# configure-pre-shared-key-for-Ansible
# this is a smple way to establish a ssh connection from control node to remote workstation node without having the need to enter password for each request
# objective is to copy the ssh key of the control node to the remote workstation's folder/file, .ssh/authorized_keys
# then we can insert the remote workstation (or ip_address) into the inventory file and create a playbook to configure remote workstation
