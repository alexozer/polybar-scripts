# Script: battery-combined-tlp

A shell script that shows the battery status.

It uses TLP and requires root privileges. Note that the icon doesn't change.


## Dependencies

* `tlp`


You may need to add `tlp-stat` command to the `/etc/sudoers` NOPASSWD of your user:

```
user ALL=(ALL) NOPASSWD: /usr/bin/tlp-stat
```


## Module

```
[module/battery-combined-tlp]
type = custom/script
exec = ~/polybar-scripts/battery-combined-tlp.sh
interval = 10
```
