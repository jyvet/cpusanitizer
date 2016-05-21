CPU Sanitizer
============

Sanitize cores from activity. Temporaraly migrate processes and threads on core 0. Might be used to run tests and benchmarks with less perturbations.

Dependencies
------------

* **taskset** [package: *taskset*] for processes migration
* **tput** [package: *ncurses*] for colors management


Running CPU Sanitizer
----------------

    % cpusan [options...]


Examples
--------

Migrate all processes on core 0:

    sudo cpusan

Migrate processes owned by user on core 0:

    cpusan

Migrate all processes on core 0 and 8:

    sudo cpusan -c 0,8

Migrate all processes on core 0, except process hpl and PID 42:

    sudo cpusan -e hpl,42

Use with color support:

    sudo cpusan --colors
