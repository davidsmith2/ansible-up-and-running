# Ansible Up & Running

## Starting the Vagrant servers

`vagrant up`

## Running the playbook

`ansible-playbook sdms-webapps.yml -l [group] --e '{"hosts": [group], "sdms_environments": [sdms_environments]}'`

## Extra variables

- hosts: dev
- sdms_environments: dev1, dev2, dev3
