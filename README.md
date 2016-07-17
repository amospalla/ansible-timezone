# ansible-timezone
* * *

## Description

Sets a host timezone.

Set the contents of /etc/timezone to the variable _timezone_.

Makes a symbolic link of file /usr/share/zoneinfo/{{ timezone }} to /etc/localtime.

## Variables

Mandatory:
- _timezone_: ie: 'Europe/Madrid'.
