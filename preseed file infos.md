# Debian 12 (bookworm)

## default.cfg

default preseed file (https://www.debian.org/releases/bookworm/example-preseed.txt)



## proxmox-base.cfg

- reboots after install

### desktop environment

- NONE

### additional packages

- qemu guest agent

### Keyboard

- de

### hostname

- testhost / unassigned-hostname

### Root Account

- None (User can use sudo)

### User

- name: test
- password: insecure

### Network connection

- None

### Network mirror

- deactivated

### Partitioning

- first scsi/sata disk
- method: lvm

### !!! NOTES !!!
- does not handle multiple Harddrives (Partitioning)



## lxde.cfg

 - reboots after install

### desktop environment

- lxde

### additional packages

- qemu guest agent

### Keyboard

- de

### hostname

- testhost / unassigned-hostname

### Root Account

- None (User can use sudo)

### User

- name: test
- password: insecure

### Network connection

- None

### Network mirror

- deactivated

### Partitioning

- first scsi/sata disk
- method: lvm

### !!! NOTES !!!
- does not handle multiple Harddrives (Partitioning)

