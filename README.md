testy-vagrant
=============

A preconfigured Ubuntu Server 14.04 Vagrant environment, complete with PHP 5.5, and PHPUnit.

Usage
=====

Copy `Vagrantfile`, `bootstrap-root.sh`, and `bootstrap-vagrant.sh` into your project's root.

Modify the installed packages in `bootstrap-root.sh` to fit your project's dependencies.

`vagrant up` to provision the new environment.

`vagrant ssh` to ssh to the testing environment.

`cd` to your project's test directory and `phpunit`.
