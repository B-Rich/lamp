minimal readme to get started.  re-working original MO lamp script for AWS

At this point only the directory structure has been re-worked for pure ansible rather than HEAT/ansible mix.  To-DO list for this project would include doing all of the following as well as writing new roles for Amazon Linux and other OS'es that may differ in supportibility from MO to FAWS.

-properly bootstrap an EC2 instance for apache/php
-include SSM
-include ScaleFT
-include sysstat
-include logrotate