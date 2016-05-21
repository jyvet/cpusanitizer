CHANGELOG
=========

V0.1
----

* Migrate temporarly processes/threads on core 0
* Restore affinity on exit
* Move user's processes only (if not run as root)
* Colors management


V0.2
----

* Fix ident issues
* Add info messages
* Add new colors
* Argument to provide CPU core set


V0.3
----

* Check if processes are still active
* Add silent mode
* Add verbose mode
* Argument to provide exclude list of process names / PIDs


V0.4
----

* Argument to choose to migrate kernel processes
* Add active mode (periodically check for new processes)
* Argument to change active mode refresh rate
* Alias to combine kernel processes migration and active mode
