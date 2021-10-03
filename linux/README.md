# Security Lab - Ubuntu Linux machine

## Vagrant

VBox configuration through `vagrant`

Provision the Machine:

`$ vagrant up`

Reprovision the machine:

`$ vagrant up --provision

Start GUI:

*Only need to do this hte first time the VM is provisioned*

```shell
$ vagrant ssh
$ startx
```

Vagrant credentials:

username: `vagrant`

password: `vagrant`

## Configuration

Configured to with a NAT interface and an interface on an internal network (`private_network`)

To configure another VirtualBox machine to communicate with this VM - configure other VMs with an Internal Network called `private_network` and and IP addres in range `192.168.50.0/24`

Hostname: `victim`

IP address: `192.168.50.40`

Internal network name: `private_network`

