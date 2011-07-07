!SLIDE

# PostgreSQL, Web Apps, and EC2

!SLIDE bullets incremental

# Running 100,000 Apps At Once

* 2000 free databases per server
* plus dedicated databases

!SLIDE bullets incremental

# EC2

* servers provisioned on demand
* from 300mb of RAM to 68gb of RAM
* sub-ms latency within EC2 zone

!SLIDE bullets incremental

# IO Performance on EBS

* Not great
* 8-volume mdadm raid
* lvm2 on top
* GNBD
* see: http://orion.heroku.com/past/2009/7/29/io_performance_on_ebs/

!SLIDE bullets incremental

# Multi-tenant

* Tried per-user schemas, not secure enough
* Shared cluster allows high density
* Shared cluster makes logging and introspection hard

!SLIDE bullets incremental

# Dedicated

* challenging to monitor performance
* constant monitoring
* regular backups
* secured ingress

!SLIDE

# Interesting Questions

!SLIDE bullets incremental

# What is my responsibility?

* You create indexes...
* I pick filesystems...
* but I get paged at 3AM when you become nonresponsive.

!SLIDE bullets incremental

# How can I put more tools in your hands?

* Fewer SIGHUP context GUC would be nice
* Particularly logging
* Host monitoring tools
* CPU, IO, free memory, etc.
* Requests welcome!

!SLIDE

# FIN
# (demos!)
# pvh@heroku.com

