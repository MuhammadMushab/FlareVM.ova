
# 🔥 Win10 FLARE VM (Malware Analysis Lab)

![Platform](https://img.shields.io/badge/Platform-Windows-blue)
![VM](https://img.shields.io/badge/VM-VirtualBox-orange)
![Use](https://img.shields.io/badge/Use-Malware%20Analysis-red)
![Level](https://img.shields.io/badge/Level-Beginner%20Friendly-green)
![Size](https://img.shields.io/badge/Size-26GB-important)

---

## 🧪 FLARE VM Desktop

![Desktop](screenshots/desktop.png)

---

## 📦 Download

Due to GitHub size limits, the VM is split into parts.

### ☁️ Google Drive

* Part 1 (13GB): [[Link]](https://drive.google.com/file/d/1FIK09feQhIfMJWa-4TO5yfsB6dRpYchK/view?usp=sharing)
* Part 2 (13GB): [[Link]](https://drive.google.com/drive/folders/1Dmie9MzzPvuK35gRKu3kfflOT17hhrN6?usp=sharing)
### ☁️ MEGA

* Part 1 (13GB): [[[Mega Folder Link ]](https://mega.nz/file/hnoVBJKI#mMsdZ5rJ2E1cKj9h413iv1AGzxnEO3yuGRjh2THrdRI)
* Part 2:(13GB): [[Mega Folder Link ](https://mega.nz/folder/Kb5GAIBa#1o_adgNgqQjgoDIS4yJDZg)]

⚠️ Download ALL parts from both links

---

## 🔐 Login Credentials

* **Username:** User
* **Password:** 1010

---

## ⚙️ FULL SETUP GUIDE

### 1️⃣ Download Files

Download ALL parts:

```bash
Win10 Pro.7z
Win10 Pro.7z.002
Win10 Pro.7z.003
```

⚠️ Keep all files in the same folder

---

### 2️⃣ Extract Files

1. Install **7-Zip**
2. only one file Extract  
3. Right-click `Win10 Pro.7z`
4. Click **Extract Here**

✔ Automatically combines all parts
✔ Output: `Win10 Pro.ova`

---

### 3️⃣ Import into VirtualBox

1. Open VirtualBox
2. Click **File → Import Appliance**
3. Select `Win10 Pro.ova`
4. Click **Next → Finish**

---

### 4️⃣ Configure Virtual Machine

After import:

#### 🧠 RAM

* Go to: **Settings → System → Motherboard**
* Set: **8GB – 12GB**

#### ⚙️ CPU

* Go to: **Settings → System → Processor**
* Set: **4 – 8 CPUs**

#### 💾 Storage

* Ensure at least **70GB free space**

---

### 5️⃣ Start the VM

1. Click **Start**
2. Login using password: `1010`

---

## 📸 Snapshot (VERY IMPORTANT)

After first boot:

1. Start VM
2. Login
3. Go to: **Machine → Take Snapshot**
4. Name it: `Clean State`

### ✅ Why Snapshot?

* Restore clean environment instantly
* Safe malware testing
* Avoid reinstalling VM

---

## ⚠️ Important Notes

* Do NOT rename split files
* Extract only from `.7z` file
* Keep all parts together
* Enable virtualization (VT-x / AMD-V)
* Recommended system: **16GB RAM or higher**

---

## 🎯 Use Cases

* Malware Analysis
* Reverse Engineering
* CTF Practice
* Cybersecurity Labs

---


## ⭐ Support

If this project helped you, give it a ⭐ on GitHub!

---
