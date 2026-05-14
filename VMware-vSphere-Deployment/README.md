# 🖥️ VMware vSphere Infrastructure Deployment Project

A full enterprise-level virtualization environment built using 
VMware vSphere, designed and implemented as a team project at ITI.

---

## 📋 Project Overview

Designed and deployed a complete VMware vSphere infrastructure 
using 3 physical servers, simulating a real enterprise datacenter 
with centralized management, shared storage, and high availability.

---

## 🏗️ Infrastructure Components

| Component | Details |
|-----------|---------|
| ESXi Hosts | 2 hosts (v6.7) |
| vCenter Server | VCSA v6.7 |
| Shared Storage | NFS Datastore (Windows Server) |
| Network | 2 vSwitches (Management/VM + Storage/vMotion) |

---

## ✅ What Was Implemented

- ESXi & vCenter Server deployment and configuration
- Datacenter and Cluster creation
- Standard vSwitch configuration with port groups:
  - Management Network
  - VM Network
  - Storage Network (NFS)
  - vMotion Network
- NFS Shared Datastore setup
- Content Library for ISO and templates
- VM creation (from ISO, Template, Clone)
- VMware Tools installation
- Templates, Snapshots, and Cloning
- Live Migration with vMotion
- High Availability (HA)
- Distributed Resource Scheduler (DRS)
- Fault Tolerance (FT)

---

## 🛠️ Technologies Used

- VMware ESXi 6.7
- VMware vCenter Server 6.7
- VMware vSphere Client
- NFS (Network File System)
- Windows Server 2019 (NFS Server)

---

## 🎓 Training Context

- Institute: Information Technology Institute (ITI)
- Track: Network & System Administration
- Related Certification: VMware vSphere / ESXi
