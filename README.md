# sudoers
This sudores file hardens the sudo command in a linux system

Here are some of the permissions set in this sudoers file:

The acess to root account with sudo su is not allowed. 
Members of the "admin" group are allowed to run commands related to networking, software, services, and processes.
Members of the "sudo" group are allowed to run commands related to networking, software, services, and processes.
There are defined command aliases such as NETWORKING (network related commands), SOFTWARE (software installation and management), SERVICES (service management), PROCESSES (process management) and others. These aliases are used to group related commands together.
There are host aliases and user aliases, which can be used to group machines and users respectively.
There are other default settings defined such as authentication timeout, environment settings and secure paths.
