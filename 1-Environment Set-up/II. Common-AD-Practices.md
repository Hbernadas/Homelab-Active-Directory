# 👷 Common Active Directory Practices

This section covers a few basic Active Directory tasks potentially in the workspace. Tasks include profile editing for users including passwords, creating and modifying service accounts, and onboarding new users. 

--

## 0. Filling the directory with pseudo-data 

- Organizational Units: Users, computers, printers, service users

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

## 🔧 3. Service Accounts

- Created a separate OU for services, for better organization.

📸 **Security Account Created**
<img width="1920" height="903" alt="1" src="https://github.com/user-attachments/assets/51918308-7c4b-4650-9228-e721bd13d01b" />

- Creating a new service account using a consisntent naming convention.

📸 **Service Account Creation**
<img width="1720" height="892" alt="1" src="https://github.com/user-attachments/assets/36ebdc16-2cca-464d-a9e0-79d760df81c3" />

- Modifying object attributes to align how a service should be (e.g. service password never expires).

📸 **Attribute Modification**
<img width="1717" height="890" alt="2" src="https://github.com/user-attachments/assets/cc5c5a08-d5d5-41c5-b244-ece0457aa543" />

- Further modification and documentation through profile editing. 

📸 **Editing object profile**
<img width="1716" height="885" alt="3" src="https://github.com/user-attachments/assets/ab772251-b89c-40a3-95c6-09c2daa4213c" />


📸 **Editing object profile (2)**
<img width="1720" height="886" alt="4" src="https://github.com/user-attachments/assets/8ecd703a-d432-484a-bf27-5189445b4e40" />

---

## ✈️ 3. Onboarding

- Created a new User Profile

📸 **New user successfully created)**
<img width="1713" height="895" alt="1" src="https://github.com/user-attachments/assets/9e0b4e2a-84c5-4a4d-8486-f9eaf68d1f84" />

- Mirroring the same attributes for the new user, such as their group membership, from a user in the same domain or a similar teammate.

📸 **Copying profile attributes from a current member to the new user**
<img width="1686" height="865" alt="2" src="https://github.com/user-attachments/assets/6c5aa6e3-5533-45e4-ace1-a8f6e8fd679a" />


---
