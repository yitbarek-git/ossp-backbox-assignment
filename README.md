# 🐧 BackBox Linux Virtualization Project

This repository documents the installation and configuration of **BackBox Linux** in a virtual environment as part of an individual assignment for the **Operating Systems and System Programming (OSSP)** course at **Bahir Dar University (BDU)**.

BackBox Linux is an Ubuntu-based distribution designed for penetration testing, security auditing, and system analysis. It includes a lightweight **XFCE desktop environment** and a powerful toolkit for vulnerability assessment, digital forensics, and network security testing.

---

## 🎯 Objectives

- **Deployment:** Successfully install BackBox Linux on a virtual machine using VMware Workstation or VirtualBox.  
- **Exploration:** Understand the operating system environment and core virtualization concepts.  
- **Filesystem Analysis:** Examine the filesystem structure and support provided by BackBox Linux.  
- **Documentation:** Record the full installation process, including challenges and solutions.

---

## ⚙️ System Requirements

### 🖥️ Hardware
- **Processor:** Dual-core or better  
- **Memory:** Minimum 2 GB RAM (4 GB recommended)  
- **Storage:** At least 20 GB free disk space  

### 💻 Software
- **Hypervisor:** VMware Workstation / Oracle VM VirtualBox  
- **OS Image:** BackBox Linux ISO  
- **Host OS:** Windows, Linux, or macOS *(Project used Windows 11)*  

---

## 🚀 Installation & Setup

- **System Check:** Verified hardware requirements using Windows Task Manager.  
- **Hypervisor Setup:** Installed VMware Workstation Pro.  
- **ISO Acquisition:** Downloaded official BackBox Linux ISO from the official website.  
- **VM Creation:**
  - Selected **Typical (Recommended)** configuration  
  - Mounted BackBox ISO image  
  - Set Guest OS: **Linux → Ubuntu 64-bit**  
  - Allocated **30 GB disk space (single file)**  
- **Optimization:**
  - Disabled 3D Graphics Acceleration  
  - Removed unnecessary devices (USB/Sound) for stability  
- **Installation:**
  - Powered on the virtual machine  
  - Completed graphical installation (language, disk, user setup)  

---

## 📂 File System Support

BackBox Linux uses the **ext4 (Fourth Extended File System)** as the primary file system.

### 🔹 Why ext4?
- High stability and reliability  
- Journaling feature prevents data corruption  
- Optimized performance for Linux systems  

### 🔹 Structure Support
Supports standard Linux directories such as:
- `/home`
- `/etc`
- `/bin`
- `/usr`

---

## 🛠️ Issues & Solutions

- **ISO vs Torrent Confusion:**  
  Only the `.iso` file was used for direct VMware installation; torrent files were not suitable.

- **Incorrect Guest OS Selection:**  
  Resolved by selecting **Ubuntu 64-bit**, which matches BackBox Linux architecture.

- **Unmounting Warning:**  
  A temporary warning appeared after installation; resolved by detaching the ISO after reboot.

---

## 🖥️ Virtualization Concepts

This project demonstrates the core components of virtualization:

- **Host Machine:** Physical system (Windows 11 PC)  
- **Hypervisor:** VMware Workstation managing virtual machines  
- **Guest OS:** BackBox Linux running in isolation  

### 🔹 Benefits of Virtualization
- Cost efficiency  
- Better hardware utilization  
- Secure and isolated testing environment  

---

## 🏁 Conclusion

This project successfully deployed BackBox Linux on a virtual machine running Windows 11. The environment is fully functional and includes tools such as Terminal and Firefox, enabling secure experimentation in cybersecurity and system analysis.

---

## 👤 Author

- **Name:** Yitbarek Kifleyohans  
- **Student ID:** BDU170274  
- **Institution:** Bahir Dar University, Institute of Technology  
- **Course:** Operating Systems and System Programming (OSSP)  
- **Instructor:** Mr. Wondmu Baye  

---