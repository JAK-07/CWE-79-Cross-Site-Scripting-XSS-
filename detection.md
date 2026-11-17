─(kali㉿Kali)-[~]
└─$ docker logs mutillidae.pc --tail 50                                                                                                                                                        
=> An empty or uninitialized MySQL volume is detected in /var/lib/mysql
=> Installing MySQL ...
=> Done!
=> Waiting for confirmation of MySQL service startup
=> Creating MySQL admin user with random password
=> Done!
========================================================================
You can now connect to this MySQL Server using:

    mysql -uadmin -pnc7vgdUahLvm -h<host> -P<port>

Please remember to change the above password as soon as possible!
MySQL user 'root' has no password but only allows local connections
========================================================================
/usr/lib/python2.7/dist-packages/supervisor/options.py:295: UserWarning: Supervisord is running as root and it is searching for its configuration file in default locations (including its current working directory); you probably want to specify a "-c" argument specifying an absolute path to a configuration file for improved security.
  'Supervisord is running as root and it is searching '
2026-11-17 07:08:27,921 CRIT Supervisor running as root (no user in config file)
2026-11-17 07:08:27,922 WARN Included extra file "/etc/supervisor/conf.d/supervisord-mysqld.conf" during parsing
2026-11-17 07:08:27,922 WARN Included extra file "/etc/supervisor/conf.d/supervisord-apache2.conf" during parsing
2026-11-17 07:08:28,093 INFO RPC interface 'supervisor' initialized
2026-11-17 07:08:28,094 CRIT Server 'unix_http_server' running without any HTTP authentication checking
2026-11-17 07:08:28,096 INFO supervisord started with pid 1
2026-11-17 07:08:29,102 INFO spawned: 'mysqld' with pid 436
2026-11-17 07:08:29,106 INFO spawned: 'apache2' with pid 437
2026-11-17 07:08:30,750 INFO success: mysqld entered RUNNING state, process has stayed up for > than 1 seconds (startsecs)
2026-11-17 07:08:30,751 INFO success: apache2 entered RUNNING state, process has stayed up for > than 1 seconds (startsecs)

┌──(kali㉿Kali)-[~]
└─$                             
