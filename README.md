# 🔋 Smart Microgrid Energy Monitoring System

## 🌍 Project Overview
The **Vidyut** is an **IoT and cloud-enabled platform** that helps communities track, manage, and optimize their renewable energy usage.  
It provides real-time visibility into **generation, storage, and consumption**, while also sending **alerts and recommendations** to grid operators for better decision-making.  

Designed to be **affordable, scalable, and community-friendly**, the system empowers both individual households and local operators to manage energy resources more efficiently.

---

## 🎯 The Problem
- Lack of **transparent monitoring** in renewable microgrids.  
- Households often face **unequal energy distribution**.  
- Manual supervision leads to **long downtimes** during failures.  
- Operators cannot easily identify **when to expand or upgrade** systems.  

---

## 💡 Our Solution
- Install sensors at both **battery units**.  
- Collect data on production, consumption, and battery health in real time.  
- Use a **GSM communication module** to transfer data to a central server.  
- Provide a **mobile application** that allows operators to:  
  - Track live energy flow  
  - Receive system alerts and recommendations  
  - Ensure fair billing and prevent disputes  
- Integrate **fuse-protected meters** at household level for reliability.  

---

## 🌟 Key Highlights
- Grid recognition using **SIM-based identification**.  
- **Data-driven predictions** for seasonal and peak loads.  
- **Simple and scalable architecture**, adaptable to rural or urban setups.  
- Operator-friendly **mobile dashboard** for monitoring and control.  

---

## 🛠️ Technology Stack

### 🔹 Software
- **Mobile App** → Flutter  
- **Backend** → Express.js with TypeScript  
- **Database** → PostgreSQL  
- **Deployment** → Docker containers orchestrated via Kubernetes  
- **Load Balancer** → Nginx  

### 🔹 Hardware
- **Controller** → ESP32  
- **Communication** → SIM900 GSM/GPRS module  
- **Sensors** →  
  - Current measurement sensor  
  - Temperature sensor for safety  
- **Power Supply** → 12V battery + regulator  

---

## 🔧 System Workflow
1. Sensors gather live grid data.  
2. Data is transmitted to the server using GSM.  
3. Backend stores and processes information in PostgreSQL.  
4. Operators use the **mobile app** to view insights and alerts.  
5. Decisions on billing, upgrades, and load distribution are made using data insights.  

---

## ✅ Benefits
- **Affordable deployment** compared to traditional monitoring solutions.  
- **Seasonal load forecasting** for proactive grid management.  
- **Reduced downtime** due to predictive maintenance.  
- **Fair and transparent billing** for households.  
- Strengthens **community resilience** in renewable energy adoption.  

---

## ⚡ Challenges & Future Enhancements
- **SIM cost optimization** → data batching to minimize expenses.  
- **Stronger data security** with encryption in upcoming versions.  
- **Geographic adaptability** by customizing hardware enclosures.  
- **Backup connectivity** using wired transmission if GSM is unstable.  

---

## 📚 References
- [Micro-Grid: Research and Sustainable Energy Systems – IIT Bombay](https://www.ese.iitb.ac.in/~suryad/Micro-Grid.pdf)
- [Current Sensor Datasheet – HandsOnTec](https://www.handsontec.com/dataspecs/ACS712-Current%20Sensor.pdf)
- [App Design Best Practices – Glide Apps](https://www.glideapps.com/blog/app-design-best-practices)

---

## 👥 Team
- **Team Name**: Humboltz  
- **Hackathon**: Smart India Hackathon 2025  
- **Problem Statement**: Renewable Energy Monitoring System for Microgrids  
- **Category**: Hardware + Software solution  
