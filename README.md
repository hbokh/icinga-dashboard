# Icinga Dashboard

## Status

Currently not actively "developed". We started using [Nagdash](https://github.com/lozzd/Nagdash) instead, which enables us to monitor multiple Nagios / Icinga instances in one dashboard through API-calls.

## Origin

This code was *forked* from [nagios-dashboard](http://github.com/foobar0815/nagios-dashboard/)

## Screenshot

![image](https://github.com/hbokh/icinga-dashboard/raw/master/screenshot.png)

## Requirements

- a working [Icinga](https://www.icinga.org/)-instance
- ido2db backend

## Installation

Put these files into WWW-root/[dir] on your server (e.g. /var/www/dash).  
Edit merlin.php and change the dbserver/dbuser/dbpassword so it suits your environment.  
Optionally rename icinga.php into index.php or create a symbolic link.
