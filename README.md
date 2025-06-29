# The OS Masters Playbook: From Core Concepts to Modern Administration

A comprehensive guide covering core operating system principles, the evolution of flagship OSes, and practical system administration in Linux and Windows.

---

## 1. Core Operating System Services

An OS manages hardware and software resources, providing essential services:

| Service                  | Description                                                                                     |
|--------------------------|-------------------------------------------------------------------------------------------------|
| User Convenience & Abstraction | Enables users to run multiple programs simultaneously without manual CPU management.          |
| Process Management       | Creates, schedules, and terminates processes for multitasking and CPU efficiency.              |
| Memory Management        | Allocates/deallocates memory to keep processes isolated and secure.                             |
| File System Management   | Organizes files and directories, abstracting physical disk storage.                             |
| Device Management        | Handles communication between applications and hardware devices via drivers.                   |
| Security & Access        | Manages authentication, authorization, and protects data and system integrity.                  |

---

## 2. Practical System Administration: A Smart City Project

### A. Linux (Ubuntu) Command-Line Implementation

#### Create Users
```bash
sudo useradd -m -s /bin/bash Milana
sudo useradd -m -s /bin/bash Yousef
sudo useradd -m -s /bin/bash ProjectLead
sudo passwd Milana
sudo passwd Yousef
sudo passwd ProjectLead
