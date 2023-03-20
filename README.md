
# Ansible Role:  `mailcow`

Ansible role to install a **dockerless** [mailcow](https://github.com/mailcow/mailcow-dockerized) application.

`mailcow` is a software written in PHP to manage data that is important for a mail system.

The actual components of the mail system access this data via their database interfaces.


I am trying to analyse and understand the PHP code using this Ansible role.

My goal is to be able to use mailcow without dependence on Docker.

Docker is not always useful, desired, usable or practical ... it is and remains a philosophical question
(and I don't want to discuss it any more!).



## Requirements & Dependencies

- mariadb
- redis
- php8
- pecl
- nginx

## Patches

I have stored my patches in a [separate repository](https://github.com/bodsch/mailcow-dockerless).


### Operating systems

Tested on

* Debian based
    - Debian 10 / 11


## Contribution

Please read [Contribution](CONTRIBUTING.md)

## Development,  Branches (Git Tags)

The `master` Branch is my *Working Horse* includes the "latest, hot shit" and can be complete broken!

If you want to use something stable, please use a [Tagged Version](https://github.com/bodsch/ansible-mailcow/tags)!


## initial login

- username: admin
- password: moohoo

----

## Author and License

- Bodo Schulz

## License

[Apache](LICENSE)

**FREE SOFTWARE, HELL YEAH!**
