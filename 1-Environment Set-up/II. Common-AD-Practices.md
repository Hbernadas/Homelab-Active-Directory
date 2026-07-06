# 👷 

This section covers a few basic Active Directory tasks potentially in the workspace. 

--

## 0. Filling the directory with pseudo-data 

-Organizational Units: Users, computers, printers, service users

📸 ****

---

## 💾 1. User Password Resetting 

📸 **Unlocking users**

- Using the Find tool to locate the user.
- IF user gets locked out, but remembers password, unlock user accordingly by checking "Unlock account", clicking Apply, then OK.

<img width="1714" height="895" alt="1" src="https://github.com/user-attachments/assets/9efe87c3-f7b0-416d-9cd2-ba9f19d986bd" />

📸 **t**

- Giving user temporary password, for resetting

<img width="1717" height="962" alt="1" src="https://github.com/user-attachments/assets/a6d881f7-1032-4926-adbf-fdf4532fd17d" />

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
