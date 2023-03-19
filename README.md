
# Ansible Role:  `mailcow`

Ansible role to install a **dockerless** [mailcow](https://github.com/mailcow/mailcow-dockerized) application.

My goal is to be able to use mailcow without dependence on Docker.

Docker is not always useful, desired, usable or practical ... it is and remains a philosophical question
(and I don't want to discuss it any more!).


`mailcow` is a software written in PHP to manage data that is important for a mail system.

The actual components of the mail system access this data via their database interfaces.


I am trying to analyse and understand the PHP code using this Ansible role.


## Requirements & Dependencies

- mariadb
- redis
- php8
- pecl
- nginx

### Operating systems

Tested on

* Debian based
    - Debian 10 / 11
