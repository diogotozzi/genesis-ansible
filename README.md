Overview
========

This is an Ansible Repository that sets a development on Ubuntu desktop machine.

Install
=============

First, install Ansible

```sh
$ sudo apt-get install software-properties-common
$ sudo apt-add-repository ppa:ansible/ansible
$ sudo apt-get update
$ sudo apt-get install ansible
```

Install Ansible Galaxy RVM

```sh
$ sudo ansible-galaxy install AerisCloud.rvm
```

Then run Ansible playbook

```sh
$ sudo ansible-playbook -i hosts playbook.yml
```
