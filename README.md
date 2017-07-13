# Rome-Box ~ Custom Ubuntu/Xenial 16.04.2 LTS Vagrant Box

## Quick Start

To start with you'll need [VirtualBox](https://www.virtualbox.org/wiki/Downloads) and [Vagrant](https://www.vagrantup.com/downloads.html), afterwards:

```
git clone https://github.com/Romerski/rome-box rome-box
cd rome-box
vagrant up
```

Then visit **http://192.168.33.30** or run `vagrant ssh`

<sup>**Check ssh config running* `vagrant ssh-config`<sup>

## Users

Username | Password | 
-------- | ---------| 
root     | root     |
ubuntu   | ubuntu   |
vagrant  | vagrant  |

## Features

### Server Stuff

Feature | Version | 
--------      | ---------| 
Web Server    | Apache 2.4  |
MySQL | 5.7
PostgreSQL | 9.6
PHP   | 7.0   |
Python  | 2.7.12  |
Node | 8.0.0
NPM | 5.2.0
Bower | 1.8.0
Git | 2.7.4
Mercurial | 3.7.3
Curl | 7.47


### Database Stuff

Database   | Username  | Password
-------- | ---------| ---------| 
MySQL     |root     | root
PostgreSQL| postgres     | postgres

### PHP Stuff

Feature | Version | 
--------| ---------| 
Xdebug   | 2.4.0 |
Composer | 1.4.2
PDO Drivers | mysql, sqlsrv
PHP Errors On | Yes
Symfony Client | Yes
