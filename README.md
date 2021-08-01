# Ansible-server-setup

## This playbook allows you to make the initial configuration of the server/servers

You need a remote server with a root user for which the ssh key is added

How to run

~~~bash
ansible-playbook -e server_ip=<your-server-ip> -e ssh_private_key_file=<path-to-your-ssh-private-key> -e remote_user=<name-user-default-ubuntu> -e ssh_public_key_file=<path-to-your-ssh-public-key> setup.yml
~~~
