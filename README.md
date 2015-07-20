# Template for Ruby on Rails App Developmettem by Ansible

## Requirements

* [VirtualBox](https://www.virtualbox.org)
* [Vagrant](http://vagrantup.com)
* [Ansible](http://www.ansible.com)

## How To Build The Virtual Machine

Vagrant:

    host $ vagrant plugin install vagrant-vbguest

Building the virtual machine:

    host $ git clone https://github.com/katsuhiko/template-rails-ansible.git
    host $ cd template-rails-ansible
    host $ vagrant up

## Create files

~/.ssh/amazon.pem

~/.aws/credentials

	[default]
	aws_access_key_id = XXXXXXXX
	aws_secret_access_key = XXXXXXXX

## How To New Rails Project

* https://github.com/RailsApps/rails-composer

## How To New Rails Plugin

* https://gist.github.com/tomoyukiinoue/7968556
* http://www.andrewhavens.com/posts/27/how-to-create-a-new-rails-engine-which-uses-rspec-and-factorygirl-for-testing/
