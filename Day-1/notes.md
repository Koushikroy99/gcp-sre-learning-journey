# Day 01 – Introduction to GCP & SRE

## 🚀 What I Learned Today

### 1. What is Google Cloud Platform (GCP)?
Google Cloud Platform is a collection of cloud services (compute, storage, networking, databases, DevOps tools, security, etc.) provided by Google.  
Enterprises use GCP to deploy applications, run infrastructure, store data, and scale globally.

### 2. Why SRE (Site Reliability Engineering)?
SRE is a discipline created by Google to manage:
- reliability  
- performance  
- scalability  
- incident response  
- monitoring & alerting  
- automation & reducing manual work (toil)

SRE acts as a bridge between **software engineering** and **operations**.

### 3. Core SRE Focus Areas
- **Availability** → Keep services up & healthy  
- **Latency** → Reduce delays in response time  
- **Performance** → Optimize systems  
- **Monitoring & Logging** → Know what’s happening inside the system  
- **Automation** → Replace manual tasks  
- **Incident Response** → Detect, respond, learn  
- **Capacity Planning** → Predict & plan for load  

### 4. Important SRE Terms (Basic Understanding)
- **SLI (Service Level Indicator)** → Actual metrics (latency, error rate, availability)  
- **SLO (Service Level Objective)** → Target (e.g., 99.9% uptime)  
- **SLA (Service Level Agreement)** → Promise to customers + penalties  

You don’t need deep understanding today — just know the basic purpose.

---

## 🌐 GCP Core Concepts (Beginner Friendly)

### Compute
Compute services provide virtual machines and managed computing options:
- **Compute Engine** → Virtual Machines (VMs)
- **App Engine** → Serverless applications
- **Cloud Run** → Run containers
- **GKE** → Kubernetes-based container orchestration

### Storage
- **Cloud Storage (Buckets)** → Object storage
- **Persistent Disks** → VM storage
- **Filestore** → Network-attached storage
- **SQL / NoSQL Databases** → Cloud SQL, Firestore, Bigtable

### Networking
- **VPC (Virtual Private Cloud)** → Private network inside GCP  
- **Subnets** → Divide VPC  
- **Routes** → How traffic moves  
- **Firewall Rules** → Allow/deny traffic  

### IAM (Identity & Access Management)
Controls:
- who can access  
- what they can access  
- how they can access

Role types:
- Basic (Owner / Editor / Viewer)  
- Predefined (specific service roles)  
- Custom (fully controlled role)  

---

## ⚙️ GCP Console Environment Overview

When you login to the GCP Console, you should know:
- **Project** → Everything in GCP lives inside a project  
- **Billing** → Linked to project  
- **Navigation Menu** → Access to all services  
- **Cloud Shell** → Built-in Linux terminal  
- **Cloud SDK (gcloud)** → CLI tool used for automation

---

## 🔍 Why Cloud Engineers + SRE Need These Basics
You must understand:
- how cloud services work  
- how networks are created  
- how applications run  
- how reliability is measured  

Today's goal was learning the environment, not doing tasks.

---

## 🎯 Summary of Day 01
- Understood what GCP is  
- Understood what SRE is  
- Learned basic SRE terms (SLI/SLO/SLA)  
- Learned core components of GCP (compute, storage, networking)  
- Explored IAM, Console, and Projects basics  

Tomorrow onwards, we’ll start doing practical tasks.  
