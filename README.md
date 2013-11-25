# Puppet Codeception Module
Puppet manifest to install Codeception on CentOS 6.4 Vagrant development server.

## Usage
### Install Codeception
To install Codeception add one of the following to your manifest:

- `class { 'codeception': }`
- `include 'codeception'`

This will [install Codeception globally][codeception_global].

[codeception_global]: http://codeception.com/install

## Requirements
The Codeception manifest requires that wget be installed.

