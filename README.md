# Asterisk 17 PBX

Docker compose container set based on Asterisk 17 (git master).

```shell
# asterisk -r
Asterisk GIT-master-a1dba820cf, Copyright (C) 1999 - 2018, Digium, Inc. and others.
Created by Mark Spencer <markster@digium.com>
Asterisk comes with ABSOLUTELY NO WARRANTY; type 'core show warranty' for details.
This is free software, with components licensed under the GNU General Public
License version 2 and other licenses; you are welcome to redistribute it under
certain conditions. Type 'core show license' for details.
=========================================================================
Connected to Asterisk GIT-master-a1dba820cf currently running on 0891fa04dc83 (pid = 1)
Core debug is still 6.
```

## Configuration

`./etc/asterisk` mounts into the container `/etc/asterisk` folder.

HTTP is currently enabled on the default port 8088 with no prefix, eg.

`http://localhost:8088/manager?action=login&username=admin&secret=[password]`

AMI is exposed on standard port 5038
