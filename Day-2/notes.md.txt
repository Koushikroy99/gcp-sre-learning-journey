# Day 02 – Creating Your First VM in Google Cloud

## 🚀 What I Learned Today

### 1. What is a VM (Virtual Machine)?
A VM is a virtual computer running inside Google Cloud.  
It works like your personal laptop but hosted on Google’s servers.

You can:
- Install software  
- Run commands  
- Host applications  
- Practice Linux/DevOps/SRE tasks  

---

## 🖥️ 2. Steps to Create a VM in GCP
### Step 1: Open the GCP Console  
Go to: console.cloud.google.com  

### Step 2: Select **Compute Engine → VM Instances**

### Step 3: Click **Create Instance**

### Step 4: Basic Settings
- **Name:** give a simple name (example: *my-first-vm*)  
- **Region & Zone:** choose closest to India (asia-south1 recommended)

### Step 5: Machine Type (Beginner Friendly)
Choose:
- **e2-micro** (Free Tier eligible)

### Step 6: Choose OS Image
Select:
- **Ubuntu 22.04 LTS (recommended for beginners)**  
  or  
- **Debian 11/12**

### Step 7: Firewall
Check:
- **Allow SSH**
- **Allow HTTP/HTTPS (optional)**

### Step 8: Click **Create**

Your VM will start in 10–20 seconds.

---

## 🔌 3. Connecting to VM (SSH)

Once VM is running:
- Click **SSH** button  
- A browser-based Linux terminal opens  
- Now you can run commands like:
  - `ls` → list files
  - `pwd` → show current directory
  - `whoami` → logged-in user
  - `uname -a` → system information  

---

## 🔥 4. Understanding Firewall Rules (Beginner Level)

### Why Firewall Rules?
They control what traffic can enter your VM.

### Important Ports
| Service | Port | Purpose |
|--------|------|---------|
| SSH | 22 | Connect to VM |
| HTTP | 80 | Access web pages |
| HTTPS | 443 | Secure web traffic |

### While creating VM:
If you check:
- **Allow SSH** → port 22 opens  
- **Allow HTTP/HTTPS** → ports 80 & 443 open  

This makes your VM reachable safely.

---

## 🎯 Summary of Day 02
- Learned what a VM is  
- Created a VM in GCP  
- Connected to VM using SSH  
- Understood basic Linux commands  
- Learned simple firewall rules (SSH, HTTP, HTTPS)  

Tomorrow, we will learn VPC (Virtual Private Cloud).
