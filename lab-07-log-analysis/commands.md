# Commands Used in Lab 07

## View Log Directory

ls /var/log

## View Contents of a Log File

cat /var/log/syslog

## View Log File with Scroll

less /var/log/syslog

## Monitor Logs in Real Time

tail -f /var/log/syslog

## View Last Lines of a Log

tail /var/log/syslog

## Search Logs for a Keyword

grep ssh /var/log/syslog

## View System Logs with systemd

journalctl

## View Recent Logs

journalctl -n 20
