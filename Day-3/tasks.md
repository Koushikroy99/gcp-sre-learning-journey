# Day 03 – Networking Tasks (Beginner)

## 🎯 Task 1: Create a Custom VPC
1. Go to **VPC network → VPC networks** in GCP Console  
2. Click **Create VPC network**  
3. Name it: `my-first-vpc`  
4. Subnet creation: choose **Custom**  
   - Example: `subnet-a` → 10.0.1.0/24, region: asia-south1  
5. Click **Create**  

---

## 🎯 Task 2: Launch a VM in Your Subnet
1. Go to **Compute Engine → VM Instances**  
2. Click **Create Instance**  
3. Select **Network → my-first-vpc**  
4. Select subnet: `subnet-a`  
5. Allow **SSH** access (default)  
6. Click **Create**  

---

## 🎯 Task 3: Connect to Your VM using SSH
1. Open the VM list  
2. Click **SSH** (browser-based)  
3. Run basic Linux commands:
ls
pwd
whoami
uname -a
**Purpose:** Make sure your VM is running and accessible  

---

## 🎯 Task 4: Check Firewall Rules
1. Go to **VPC network → Firewall rules**  
2. Observe default rules:
   - `allow-ssh` → TCP 22  
   - `allow-rdp` → TCP 3389  
   - `allow-internal` → TCP/UDP  
3. Optional: create a new rule to allow **HTTP (port 80)**  

---

## 🎯 Task 5: Stop & Start Your VM
1. Stop the VM  
2. Start the VM again  
3. Observe how the **external IP** may change (if ephemeral)  

---

## ✔ Summary
- Created VPC and subnet  
- Launched VM inside subnet  
- Connected to VM using SSH  
- Checked firewall rules  
- Practiced stopping & starting VM  

**Goal:** Be comfortable with **GCP networking basics** and launching **your first VM**.



