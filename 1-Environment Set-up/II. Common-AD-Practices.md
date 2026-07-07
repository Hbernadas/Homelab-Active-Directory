# 👷 

This section covers a few basic Active Directory tasks potentially in the workspace. 

--

## 0. Filling the directory with pseudo-data 

-Organizational Units: Users, computers, printers, service users

📸 **AD**
<img width="1721" height="891" alt="1" src="https://github.com/user-attachments/assets/19b1d590-c3ef-4f01-8964-8402c45aa985" />

---

## 🔐 1. User Password Resetting 

- Using the Find tool to locate the user.
- IF user gets locked out, but remembers password, unlock user accordingly by checking "Unlock account", clicking Apply, then OK.
  

📸 **Unlocking users**
<img width="1714" height="895" alt="1" src="https://github.com/user-attachments/assets/9efe87c3-f7b0-416d-9cd2-ba9f19d986bd" />


- Giving user temporary password, so they can choose and reset on their own when login.
  

📸 **Password resetting**
<img width="1717" height="962" alt="1" src="https://github.com/user-attachments/assets/a6d881f7-1032-4926-adbf-fdf4532fd17d" />

---

## 🔨 2. Modifying User Profiles

- Changing user data such as descriptions, email, phone number, etc.
  

📸 **"User description and number modified**
<img width="1720" height="890" alt="1" src="https://github.com/user-attachments/assets/86bc4725-4d50-4d30-b7b7-03357d83c974" />

- Adding Objects to Group members.

📸 **Selecting certain groups to be added**
<img width="1715" height="791" alt="1" src="https://github.com/user-attachments/assets/dfd6e795-fbf4-4f4c-9931-87499ff4c8d1" />

- Moving Users/Objets to a different OU

📸 **Finding Users or Objects and click the move function**
<img width="1715" height="893" alt="1" src="https://github.com/user-attachments/assets/7a6ad9af-4615-4b91-bb61-1682df53324b" />

📸 **User has been moved successfully**

<img width="1717" height="889" alt="1" src="https://github.com/user-attachments/assets/497c400c-fa35-4f19-a08a-3a2347d4591c" />

---

## 🏰 3. Promoting to Domain Controller

- Promoted the server to a DC using the post-installation wizard
- Created a **new forest** named `root.local`
- Rebooted the machine after setup completed

📸 **Successful Promotion**

<img width="1920" height="1043" alt="3" src="https://github.com/user-attachments/assets/ed96a0f4-c21b-4048-9965-0f3fdeb66e16" />


---
