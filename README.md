# Vagrant Guest Environmnent for Symony2 Development

Host created with puppet contains: 

* Ubuntu 12.10 (quantal-64 - can be use on Mac hosts)
* Apache22
* MySQL
* PHP 5.4 (inc. php-xdebug, php-intl)
* Varnish3


**Installation

Prerequisites:
* git
* VirtualBox (https://www.virtualbox.org/wiki/Downloads)
* Vagrant (vagrantup.com)

Steps:
* Clone it: `git clone git@github.com:mattcarp/vagrant-puppet-symfony2.git`
* CD into the directory
* Run vagrant: `vagrant up`
