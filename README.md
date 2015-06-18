# Openwayback Vagrant

## Introduction

The is a development environment virtual machine for Openwayback. It should work on any operating system that supports VirtualBox and Vagrant.

## Requirements

1. [VirtualBox](https://www.virtualbox.org/)
2. [Vagrant](http://www.vagrantup.com/)

## Use

1. `git clone https://github.com/ruebot/openwayback_vagrant`
2. `cd openwayback_vagrant`
3. `vagrant up`

## Connect

You can connect to the machine via the browser at [http://localhost:8000](http://localhost:8000).

You can connect to the machine via ssh: `ssh -p 2222 vagrant@localhost`

The default VM login details are:
  - username: vagrant
  - password: vagrant

## Environment

- Ubuntu 14.04
- Apache 2.26
- Tomcat 7.0.52
- Solr 4.2.0
- Java 8 (Oracle)

## Authors

* [Nick Ruest](https://github.com/ruebot)
