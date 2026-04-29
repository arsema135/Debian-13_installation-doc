# Debian-13_installation-doc
Debian 13 installation documentation

## Introduction
This document shows the steps followed to install Debian 13 on Oracle VirtualBox. It explains how the system was set up and what was done during the installation process.

## Objective
The goal of this work is to successfully install Debian 13 in a virtual machine and understand the basic installation process of a Linux system.

## Requirements
- Oracle VirtualBox installed
- Debian 13 ISO file
- Minimum 2GB RAM (4GB recommended)
- At least 20GB virtual disk space

## Installation Process

### 1. Create Virtual Machine
- Open VirtualBox
- Click  New
- Name the machine “Debian 13”
- Set type to Linux and version to Debian (64-bit)

### 2. Memory Setup
- Assign RAM (2048 MB minimum, 4096 MB recommended)

### 3. Hard Disk Setup
- Create a new virtual hard disk
- Choose VDI format
- Select dynamically allocated storage
- Set size to at least 20GB

### 4. Attach ISO File
- Go to Settings → Storage
- Select empty disk
- Mount the Debian 13 ISO file

### 5. Start Installation
- Start the virtual machine
- Choose **Graphical Install**
- Select language, location, and keyboard layout

### 6. System Configuration
- Set hostname
- Create user account and password

### 7. Disk Partitioning
- Choose “Guided – use entire disk”
- Select the virtual disk
- Confirm changes and continue

### 8. System Installation
- Wait while base system is installed
- Select required software packages

### 9. Boot Loader
- Install GRUB boot loader
- Choose the main disk for installation

### 10. Finish Setup
- Restart the system
- Remove ISO file if needed

## Challenges Faced
- Installation was slow due to limited RAM
- Some confusion during disk partitioning
- Incorrect ISO selection at first attempt

## Conclusion
The Debian 13 installation was completed successfully using VirtualBox. This process helped in understanding how Linux systems are installed and configured in a virtual environment.
