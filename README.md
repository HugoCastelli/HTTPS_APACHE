# HTTPS avec Cerbot sur un Apache Serveur

Cerbot : [lien](https://certbot.eff.org/).

## Installation

```bash
$ sudo apt-get update
$ sudo apt-get install software-properties-common
$ sudo add-apt-repository universe
$ sudo add-apt-repository ppa:certbot/certbot
$ sudo apt-get update
$ sudo apt-get install certbot python-certbot-apache
$
$ sudo certbot --apache
```
