# Ansible Preprovision

This script will preprovision a fresh Archlinux ARM installation and get it ready for its first Ansible run.

## Instructions

1. Log into your new box as `alarm` with password `alarm`
2. `su - root` with password `root`
3. `curl -s https://raw.githubusercontent.com/bmcclure/ansible-preprovision/master/10-root.sh | bash`
4. Provision with Ansible!
