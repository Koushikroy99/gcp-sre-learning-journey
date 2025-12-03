# Day 02 – Tasks (Beginner)

## 🎯 Task 1: Create Your First VM
- Go to **GCP Console → Compute Engine**
- Click **Create Instance**
- Select:
  - Machine Type → e2-micro (Free Tier)
  - OS → Ubuntu 22.04 LTS
  - Region → closest to your location
- Click **Create**
- Confirm the VM is running

---

## 🎯 Task 2: Connect to Your VM using SSH
- Go to **VM Instances** list
- Click **SSH** (browser-based)
- Run these commands:
  - `ls` → list files
  - `pwd` → show current location
  - `whoami` → show user
  - `uname -a` → system info

---

## 🎯 Task 3: Check Firewall Rules
- During VM creation, check **Firewall** section
- Confirm:
  - SSH (port 22) is allowed
  - HTTP/HTTPS — optional only if hosting websites

**Why important?**  
Without port 22 allowed, SSH will not work.

---

## 🎯 Task 4: Stop & Start Your VM
- Stop the VM from the console  
- Start the VM again  
- Observe:
  - External IP changes (if ephemeral)

---

## ✔️ No advanced tasks today  
Today’s focus is only:
- VM creation  
- SSH login  
- Basic Linux  
- Understanding firewall rules  
- VM lifecycle (start/stop)
