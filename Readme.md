# 📌 Project: Linux Logical Volume Manager (LVM) on AWS EC2
## 🚀 Overview

### This project demonstrates hands-on implementation of Linux Logical Volume Manager (LVM) using:

* Amazon Web Services
* Amazon EC2
* Amazon EBS
* Linux (Ubuntu)

### The goal was to understand and implement:

* Physical Volumes (PV)
* Volume Groups (VG)
* Logical Volumes (LV)
* Extending & Reducing Storage
* Adding new disk to existing Volume Group
* Managing storage dynamically without downtime

## 🛠️ Architecture
1. Created EC2 instance
2. Attached multiple EBS volumes (10GB, 15GB, 20GB)
3. Configured LVM on attached disks
4. Created logical volumes
5. Mounted volumes
6. Extended and reduced logical volumes
7. Added new disk dynamically to volume group
