# Graylog

This content pack feeded by UDP/10514 syslog.
The Input has some regex extractors to find easly answers about some questions like "who created this user?" or "which service has stopped on which server ?"
It has also some dashboards and some streams to follow the daily operations on CentOS 7 Linux servers.

How to setup :

It's recommended to redirect all Linux logs to syslog like ;

* . * @graylog-server:10514

Greetings.

Monitoring.World
