## Sandbox vagrant

## Install
- [VertualBox](https://www.virtualbox.org/wiki/Downloads)
- [Vagrant](https://www.vagrantup.com/downloads.html)

## Setups
- Add box
  - `vagrant box add centos/7`
- Start
  - `Vagrant up`
- Config
  - `vagrant ssh-config --host vagrant >> ~/.ssh/config`

- We might make selinux disabled. (CentOS)
  - `sudo vi /etc/sysconfig/selinux`
    - `SELINUX=disabled`

## Commands
- Check status
  - `vagrant status`
- SSH
  - `vagrant ssh`
- Stop
  - `vagrant halt`
- Check ssh config
  - `vagrant ssh-config`
