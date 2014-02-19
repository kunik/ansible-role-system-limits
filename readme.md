Ansible System-limits
=====================

Setup ulimits and sysctl

Requirements
------------

No

Role Variables
--------------

```
system_limits:
  ulimits:
    - root soft nofile 65536
    - ...
  sysctl:
    - { name: 'net.ipv4.tcp_tw_recycle', value: '1' }
    - ...
```

Dependencies
------------

No

License
-------

BSD

