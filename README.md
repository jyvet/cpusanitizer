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


Example
-------

Use in root to migrate all processes:
    sudo cpusan

Use with color support:

    cpusan --colors
