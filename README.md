# Vagrant on Rails

## Usage

Building the virtual machine is this easy:

```
$ git clone git@github.com:trunk-inc/vagrant-rails.git
$ cd vagrant-rails
$ vagrant up
```

That's it.

After the installation has finished, you can access the virtual machine with

```
$ vagrant ssh
Welcome to Ubuntu 14.04.6 LTS (GNU/Linux 3.13.0-170-generic x86_64)

 * Documentation:  https://help.ubuntu.com/

  System information as of Thu Jun  6 02:56:26 UTC 2019

  System load:  0.03              Processes:           75
  Usage of /:   4.5% of 39.34GB   Users logged in:     0
  Memory usage: 17%               IP address for eth0: 10.0.2.15
  Swap usage:   0%                IP address for eth1: 192.168.33.10

  Graph this data and manage this system at:
    https://landscape.canonical.com/

New release '16.04.6 LTS' available.
Run 'do-release-upgrade' to upgrade to it.


Last login: Thu Jun  6 02:56:27 2019 from 10.0.2.2
vagrant@vagrant-ubuntu-trusty-64:~$ ruby -v
ruby 2.6.3p62 (2019-04-16 revision 67580) [x86_64-linux]
```

Enjoy! 🤣
