# Table content of Package and Service Management.
- [Package Mangement](#package-management)
  * [Test1](#test1)
    + [Test2](#test2)
- [Service Management](#service-management)
- [Vim Review](#vim-review)
- [Conclusions](#conclusions)

# Package Management
## Introduce about some command for manage package install
## Yum Overview
## Dnf Overview
# Service Management
## systemd
> Systemd is a system and service manager and like the most major Linux distributions the **init** deamon was replaced by systemd in CentOS. One of the main functions of systemd is to manage the services, devices, mount pints, sockets and other entities in a Linux system. Each of these entity that are managed by systemd is called unit. Eachs unit is defined by a unit file (configuration) which is located in one of the following directories.
> /usr/lib/systemd/system/ -> Unit files distributed with installed packages. Do not modify unit files in this location.
> /run/systemd/system/ -> Unit files that are dynamically created at runtime. Changes in this directory are lost when rebooted.
> /etc/systemd/system -> Unit files created by systemctl enable and custome unit files created by system administrators.
> 
## systemctl
> systemctl is the command line tool you can to control and manage service in systemd. Let's noew take a look at the some of the important systemctl commands for service managerment.
List Service Units and Unit files:
1. List all the units that are loaded.
```
# systemctl list-units
```
2. List only units of type service
```
# systemctl list-units -t service
```
3. List all installed unit files of type service
```
# systemctl list-unit-files -t service
```
# Vim Review
# Conclusions
