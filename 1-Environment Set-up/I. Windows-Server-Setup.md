# 🛠️ Windows Server 2025 Setup

In this stage, I installed and configured **Windows Server 2025** as the Domain Controller (DC) for my lab environment in a virtual machine. The process included downloading VMware and the most recent ISO file for windows server, installing Active Directory Domain Services, and promoting the server to a DC.

---

## 💾 1. Installation

- Created a new virtual machine in **VMware** with the following specs:
  - 6 GB RAM
  - 2 CPUs
  - 60 GB virtual hard drive
- Mounted the **Windows Server 2025 ISO** and completed the installation.
- Selected the **Standard Evaluation (Desktop Experience)** during setup.

📸 **Completion of Installation Setup**

<img width="1918" height="1021" alt="1" src="https://github.com/user-attachments/assets/48e2f21d-5d24-4915-a586-a4a9d24be47e" />

---

## 🧱 2. Installing AD DS Role

- Opened **Server Manager**
- Selected **Add Roles and Features**
- Installed the **Active Directory Domain Services (AD DS)** role

📸 **"Add Roles and Features Wizard" with AD Selected**

<img width="1920" height="1018" alt="2" src="https://github.com/user-attachments/assets/0ac83233-db72-4a04-8211-1222330397de" />

---

## 🏰 3. Promoting to Domain Controller

- Promoted the server to a DC using the post-installation wizard
- Created a **new forest** named `root.local`
- Rebooted the machine after setup completed

📸 **Successful Promotion**

<img width="1920" height="1043" alt="3" src="https://github.com/user-attachments/assets/ed96a0f4-c21b-4048-9965-0f3fdeb66e16" />


---
