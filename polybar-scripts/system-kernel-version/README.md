# Script: system-kernel-version

A script that shows the running kernel version.


## Module

```
[module/system-kernel-version]
type = custom/script
exec = uname -r
interval = 1024
```
