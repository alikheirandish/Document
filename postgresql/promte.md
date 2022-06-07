# promote slave to master

1) Make sure that old master node is down.

2) Check existence of "promote_trigger_file" parameter in postgresql.conf config file in new master.

3) Touch the file set in "promote_trigger_file" parameter in postgresql.conf config file in new master.

4) Check promotion in  postgresql log located at /var/log/postgresql directory in new master.
