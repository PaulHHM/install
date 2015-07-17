# Installing DeskPRO

This repository contains a set of Ansible playbooks that you can use to install
DeskPRO and its dependencies (MySQL, Elasticsearch) to a single server. These
playbooks can currently be used with:

* Ubuntu 14.04
* Ubuntu 15.04
* Debian 8.1
* CentOS 7

## Using scripts

To run the install, you have two options:

1: Run a command on your server:

Ubuntu or Debian:
`wget -q -O - https://www.deskpro.com/go/install.sh | sudo bash`

Centos:
`curl -s -L https://www.deskpro.com/go/install.sh | sudo bash`

2: Use git to clone the repository and run `sudo deskpro-install.sh`

```
git clone https://github.com/DeskPRO/install.git
cd install
sudo ./deskpro-install.sh
```

### Minimum requirements

You will need a server with *at least `1GB` of RAM* to properly run DeskPRO and
its dependencies.

You will need root access to the server you want to install DeskPRO into, or be
able to use `sudo`.

## DeskPRO Virtual Machines

You can use the links below to download ready made virtual machines with
DeskPRO pre-installed for:

- [Virtual Box](https://s3.eu-central-1.amazonaws.com/deskpro/DeskPRO-Helpdesk-VirtualBox.ova)
- [VMWare](https://s3.eu-central-1.amazonaws.com/deskpro/DeskPRO-Helpdesk-VMWare.zip)
