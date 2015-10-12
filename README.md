## Cacti plugins for server monitoring

This is a set of cacti graphs and templates for monitoring Linux servers through snmp. Some of them are based on [Percona Monitoring Plugins](https://www.percona.com/doc/percona-monitoring-plugins/1.1/index.html).


Now added the following graphs:

- Context Switches  - Context switches at system from /proc/stat
- CPU Usage - Graph that describe cpu load (userspace, kernelspace and idle)
- CPU IOWait - Amount on time cpu spent waiting for input-output
- Forks and Clones - This graph count procces creation
- Softirq - Amount of time cpu spent on softirq handling
- Swap usage - swap in and out data (pspwpin & pswpout from /proc/vmstat)
- I/O Operations - Count of comleted reads&writes at all disks
- Disks Operations Completed - Completed reads and writes operations
- Disks Operations Time Spent - Time that reads and writes elapsed 
- Network Stack - COmmon Counters for network stack
