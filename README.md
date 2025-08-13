# 🔐 TRUSTLOCKER FS – SECURE FILE SYSTEM SOFTWARE

⚠ **Note:** This mini software is in its **initial stages** and currently intended for **demo purposes only**.

---

## 🆔 Demo Login Credentials
| Role   | Username | Password  |
|--------|----------|-----------|
| Admin  | `admin`  | `admin123` |
| User   | `user`   | `user123`  |
| Guest  | `guest`  | `guest123` |

---

## 📌 Overview
**TrustLocker FS** is a **lightweight, secure file system application** designed to protect sensitive files with a clean, user-friendly interface.  
It follows the **CIA Triad principles**:

- **Confidentiality** → XOR-based encryption for all files.  
- **Integrity** → SHA-256 hash verification ensures files are not tampered with.  
- **Availability** → Role-based access ensures proper permissions for **Admin**, **User**, and **Guest**.

---

## ✨ Key Features

### 1️⃣ Role-Based Access Control
- **Admin** → Full access (create, read, edit, delete).  
- **User** → Create & read files, limited edit permissions.  
- **Guest** → Read-only access to selected files.

### 2️⃣ Advanced File Security
- XOR encryption for **confidentiality**.  
- SHA-256 hashing for **integrity checks**.  
- Prevents unauthorized **external modifications**.

### 3️⃣ User-Friendly GUI
- Forward/backward navigation buttons.  
- In-app file viewing & editing.  
- Folder-like clickable file icons.

### 4️⃣ Multi-File Support
- Create & save multiple `.txt` files with **custom names**.  
- Role-based file access.

### 5️⃣ Lightweight & Fast
- Low system resource usage.  
- Quick encryption, decryption, and access.

---

## 💡 Why Use TrustLocker FS?
- 🛡 Protect sensitive data from unauthorized access.  
- ✅ Maintain file integrity with **automated hash verification**.  
- 📂 Manage all files **inside a secure GUI**.  
- 🎯 Perfect for **cybersecurity students, red teamers**, or anyone needing secure file storage.

---

## 🚀 Getting Started

1. **Launch** the application.  
2. **Log in** using the demo credentials above.  
3. Navigate via **ribbon & folder icons**.  
4. **Create, edit, or view** files as per your role.  

**File Storage Details:**
- All files are stored in the **`saved_files`** folder.  
- Opening them outside the software will show **encrypted text**.  
- To decrypt, open them **inside TrustLocker FS**.  
- If an external modification is detected, the app will warn you.

---

## 👨‍💻 Author
**Name:** Rashid Iqbal  
**GitHub:** https://github.com/NoxVesper  
📧 **Email:** echoinject@gmail.com  

💬 *Suggestions for improvements or bug reports are highly appreciated!*  
