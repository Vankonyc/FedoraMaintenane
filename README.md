Informatipon about both scripts:

These script combining commands and tools already preinstalled into the system.


fedoracalenUP is simple version providinf following options:

1 - DNF package cache
2 - Unused dependencies
3 - DNF repository metadata/cache
4 - Crash reports and old coredumps
5 - Rotated/compressed logs
6 - systemd journal logs older than 3 days
7 - Temporary files
8 - User application caches

9 - CLEAN ALL

fedoramaintenance provides more functionalities: 

1 - DNF package cache
2 - Unused dependencies
3 - DNF repository metadata/cache
4 - Crash reports and old coredumps
5 - Rotated/compressed logs
6 - systemd journal logs older than 3 days
7 - Temporary files
8 - User application caches
9 - CLEAN ALL
10 - Disk usage analyzer
11 - Find 20 largest files
12 - Flatpak maintenance
13 - Kernel check
14 - DNF / RPM health check
15 - Failed systemd services
16 - Current boot error log
17 - SSD / NVMe TRIM
18 - Btrfs usage / health
19 - System information


INSTALLATION INSTRUCTIONS

sudo install -m 755 ~/Documents/fedoracleanUP /usr/local/bin/fedoracleanUP
sudo install -m 755 ~/Documents/fedoramaintenance /usr/local/bin/fedoramaintenance

USAGE:

Always run with sudo:

sudo fedoracleanUP
or
sudo fedoramaintenance


Enjoy
