Project to hold the source code of log4net from http://github.com/sidecut/log4net,
forked from http://github.com/apache/log4net to apply LOG4NET-27.patch,
which created a new property: MaxDateRollBackups.

LOG4NET-27.patch is found at https://issues.apache.org/jira/browse/LOG4NET-27:
"A maximum of backup files exist when rolling files on file size, but not for rolling on date/time. 
This can be implemented with the same config key : MaxSizeRollBackups"
