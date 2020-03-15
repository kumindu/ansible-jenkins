# Ansible Installation

```
$ sudo apt update
$ sudo apt install software-properties-common
$ sudo apt-add-repository --yes --update ppa:ansible/ansible
$ sudo apt install ansible

```

# Jenkins Installation

First thing you have change config file

Ansible Playbook for Implement Jenkins.

```
ansible-playbook -i <awsserver_url>, jenkins.yml
```
