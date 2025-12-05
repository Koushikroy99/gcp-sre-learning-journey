# Day 03 – Introduction to GCP Networking

## 🌐 1. What is a VPC?
A **Virtual Private Cloud (VPC)** is your **private network in Google Cloud**.  

It allows you to create and manage **VMs, containers, and other resources** in a secure environment.  

**Key Points:**
- Each project can have **multiple VPCs**  
- VPCs are **global**, but subnets are **regional**  
- Helps organize resources and manage network traffic  

---

## 🏗 2. What is a Subnet?
A **subnet** is a **smaller network inside a VPC**, used to divide your network by region.  

**Example:**
VPC: my-vpc → 10.0.0.0/16
├─ Subnet-a → 10.0.1.0/24 (region: asia-south1)
└─ Subnet-b → 10.0.2.0/24 (region: us-central1)

**Purpose of Subnets:**
- Organize resources per region  
- Control IP address allocation  
- Apply firewall rules for security  

---

## 🛣 3. What is a Route?
**Routes** tell traffic **where to go** inside your network.  

**Default Route:**  
- Directs traffic to the **internet** if no other route matches  

**Custom Routes:**  
- Can be created to send traffic to **specific VMs, VPNs, or internal networks**  

---

## 🔥 4. What are Firewall Rules?
**Firewall rules** control **incoming and outgoing traffic** to your VMs.  

- **Ingress** → traffic coming **into VMs**  
- **Egress** → traffic leaving **VMs**  

**Default rules in GCP:**
- `allow-ssh` → TCP 22 (for SSH access)  
- `allow-rdp` → TCP 3389 (for Windows RDP access)  
- `allow-internal` → TCP/UDP for internal VPC traffic  

**Tip for beginners:**  
- Only allow traffic you actually need for security  

---

## 🎯 Key Takeaways
- **VPC** = private network in GCP  
- **Subnet** = smaller network inside VPC, regional  
- **Route** = path for network traffic  
- **Firewall** = controls access to your VMs  

**Goal:** Understand the **networking basics** in GCP before launching your VMs
- **Firewall** = controls access to your VMs  

**Goal:** Understand the **networking basics** in GCP before launching your VMs.
