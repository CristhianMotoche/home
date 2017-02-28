# My configuration files
## Requirements
Install [ansible](http://docs.ansible.com/intro_installation.html).

## Run
Run the following command:
```
$ ansible-playbook playbook.yml -u root -vvvv
```
If there is any error with the SSH keys, add the following
instruction at the beginning of the command: `ANSIBLE_SSH_PIPELINING=y`
