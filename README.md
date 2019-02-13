# LWP-Dev

A Wordpress development environment built on top of docker and vagrant.

# Host Requirements:
  - Vagrant
  - Ansible

### Tech

LWP-Dev uses a number of open source projects to work properly:

* [Virtualbox](https://www.virtualbox.org/) - VirtualBox provides powerful x86 and AMD64/Intel64 virtualization
* [Vagrant](https://www.vagrantup.com/) - Development Environments Made Easy
* [Ansible](https://www.ansible.com/) - Ansible is a radically simple IT automation.
* [Docker - Wordpress](https://hub.docker.com/_/wordpress/) - The WordPress rich content management system.
* [Docker - Mariadb](https://hub.docker.com/_/mariadb) - MariaDB is a community-developed fork of MySQL

And of course LWP-Dev itself is open source with a [public repository](https://github.com/kedwards/lwp-dev)
 on GitHub.

### Installation

LWP-Dev requires [Vagrant](https://www.vagrantup.com/) v2.2.3+ and [Ansible](https://www.ansible.com/) v2.7+  to run.

Install the dependencies, configure machines.yml and start the server.

    $ cd lwp-dev
    $ vagrant up
