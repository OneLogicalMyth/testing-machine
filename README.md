# Description
I use this script to quickly build myself a temporary machine, should the need arise.

# Running
Install Ubuntu 16.04 LTS as per normal and ensure the `openssh-server` package is installed. On your Ansible machine you will need `sshpass` installed if you wish to use password auth.

Download the Nessus deb file and Kali ova files to the directory `files` and then run with the following command.

`ansible-playbook -i inventory build.yml`
