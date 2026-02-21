# RAID-5-Storage-Spaces-HotSpare
This lab demonstrates the deployment of a RAID 5 (Parity) configuration in Windows using Storage Spaces via PowerShell. It covers disk preparation, storage pool creation, virtual disk provisioning, GPT initialization, NTFS formatting, and hot spare configuration to ensure redundancy and resiliency.

🗄 Windows RAID 5 – Storage Spaces Lab

📌 Project Overview

This project demonstrates the implementation of a RAID 5 (Parity) configuration in Windows using Storage Spaces and PowerShell.

The lab simulates an enterprise storage environment where redundancy, resiliency, and automated recovery are required.

🎯 Objectives

Create a Storage Pool using multiple physical disks

Configure a RAID 5 (Parity) Virtual Disk

Initialize and format the volume (GPT + NTFS)

Configure a Hot Spare disk for automatic failover

Validate storage health and resiliency status

🛠 Technologies Used

Windows Server / Windows 10+

PowerShell

Storage Spaces

NTFS

GPT Partition Style

🧱 Architecture

RAID Level: RAID 5 (Parity)
Minimum Disks: 3
Additional Disk: 1 Hot Spare

Example setup:

Disk 1 – Active

Disk 2 – Active

Disk 3 – Active

Disk 4 – Hot Spare

Usable capacity: (N - 1) disks
