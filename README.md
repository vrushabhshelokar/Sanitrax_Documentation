# 🚀 SaniTrax

### Smart Public Toilet Monitoring & Maintenance System

> AI-Powered & IoT-Enabled Sanitation Monitoring Platform for Real-Time Public Toilet Management

![Status](https://img.shields.io/badge/Status-Working%20MVP-success)
![Hackathon](https://img.shields.io/badge/HackGenX-2026-blue)
![Team](https://img.shields.io/badge/Team-ThreeBits-orange)
![Deployment](https://img.shields.io/badge/Deployment-Partial-yellow)

---

## 📖 Overview

SaniTrax is an intelligent sanitation monitoring platform that combines **Artificial Intelligence, IoT Sensors, Cloud Infrastructure, and Role-Based Applications** to improve public toilet maintenance and hygiene management.

Traditional public sanitation systems operate reactively, where maintenance begins only after complaints are raised. SaniTrax transforms this process into a **proactive and data-driven ecosystem** by enabling:

* Real-time facility monitoring
* AI-based cleanliness verification
* Citizen feedback collection
* Automated maintenance workflows
* Usage and water-level tracking

The platform was developed during **HackGenX 2026** and successfully reached the **shortlisted stage**.

---

# 🎯 Problem Statement

Public toilets face several operational challenges:

❌ No real-time monitoring

❌ No automated cleanliness verification

❌ Delayed maintenance response

❌ Poor accountability mechanisms

❌ Lack of actionable operational insights

As a result, sanitation issues remain unresolved until users manually report them, leading to hygiene risks and poor public experiences.

---

# 💡 Solution

SaniTrax introduces a centralized ecosystem powered by AI and IoT technologies.

The platform consists of four integrated modules:

## 👥 Citizen Web Portal

Allows citizens to:

* Discover nearby public toilets
* Access toilet information
* Scan toilet-specific QR codes
* Submit cleanliness ratings
* Upload complaints and images
* Provide maintenance feedback

---

## 🧹 Janitor Mobile Application

Enables maintenance staff to:

* Receive cleaning assignments
* Upload before/after cleaning images
* Update task status
* Receive maintenance alerts
* Track assigned facilities

---

## 🤖 AI Cleanliness Verification Engine

A custom-trained **YOLOv8 Computer Vision Model** capable of detecting sanitation-related conditions using **13 trained classes**.

The AI system assists in:

* Cleanliness assessment
* Image validation
* Maintenance prioritization
* Automated decision support

---

## 📊 Admin Dashboard

Provides administrators with:

* Real-time toilet monitoring
* Complaint management
* Staff activity tracking
* Usage analytics
* Water-level monitoring
* Performance reporting

---

# 🏗️ System Architecture

```text
Citizen
   │
   ▼
QR Code Scan
   │
   ▼
Toilet Specific Feedback Portal
   │
   ▼
Appwrite Backend
   │
   ├──────────────► Admin Dashboard
   │
   ├──────────────► Janitor Application
   │
   └──────────────► AI Verification Engine

ESP32 + Sensors
   │
   ▼
Real-Time Data Stream
   │
   ▼
Appwrite Backend
```

---

# 🔄 User Workflow

```text
Citizen Visits Public Toilet
            │
            ▼
      Scan QR Code
            │
            ▼
 Opens Toilet-Specific Page
            │
            ▼
 Submit Rating / Complaint
            │
            ▼
 Upload Images (Optional)
            │
            ▼
 Data Stored in Appwrite
            │
            ▼
 Admin Dashboard Updates
            │
            ▼
 Janitor Receives Task
            │
            ▼
 Issue Resolved
```

---

# ⚙️ Technology Stack

## Frontend

* React.js
* Vite
* Tailwind CSS
* React Router

## Mobile Application

* Flutter

## Backend & Cloud

* Appwrite
* Appwrite Authentication
* Appwrite Database
* Appwrite Storage
* REST APIs
* Cloudflare Functions

## Artificial Intelligence

* Python
* YOLOv8
* TensorFlow
* OpenCV

## IoT Hardware

* ESP32
* PIR Motion Sensor
* HC-SR04 Ultrasonic Sensor

## Deployment

* Vercel
* Cloudflare
* Netlify

---

# 📡 IoT Integration

SaniTrax uses real-time sensor infrastructure to monitor restroom conditions.

### PIR Motion Sensor

Tracks restroom occupancy and usage activity.

### Ultrasonic Sensor

Monitors water levels and identifies shortages.

### ESP32

Acts as the communication layer between sensors and cloud infrastructure.

This enables real-time operational visibility without requiring manual inspection.

---

# 🤖 AI Cleanliness Verification

The platform incorporates a custom-trained **YOLOv8 Computer Vision Model** developed during the hackathon.

### Capabilities

* Detect sanitation-related conditions
* Analyze uploaded toilet images
* Assist cleanliness scoring
* Support maintenance decisions
* Generate intelligent alerts

### Training

* YOLOv8 Architecture
* 13 Custom Classes
* Real-world sanitation image dataset

---

# ⭐ Key Features

### Citizen Experience

* QR-Based Toilet Identification
* Location Discovery
* Interactive Feedback Forms
* Complaint Submission
* Image Upload Support

### Administrative Features

* Real-Time Monitoring Dashboard
* Complaint Tracking
* Staff Performance Analytics
* Maintenance Reporting

### Maintenance Features

* Cleaning Task Management
* Alert Notifications
* Before/After Image Verification

### Intelligent Features

* AI-Based Cleanliness Assessment
* IoT-Based Usage Monitoring
* Water Availability Tracking

---

# 👨‍💻 My Contributions

### Role

Frontend & React Lead

### Responsibilities

* Developed the complete Citizen Web Portal
* Built QR-based feedback workflow
* Implemented toilet-specific complaint pages
* Integrated map-based toilet discovery
* Developed responsive user interfaces
* Configured React Router navigation
* Integrated frontend with Appwrite backend
* Collaborated on testing and final deployment

---

# 📈 Impact

SaniTrax delivers measurable operational improvements:

✅ Reduced dependency on manual inspections

✅ Improved maintenance accountability

✅ Enabled real-time facility monitoring

✅ Supported multiple toilet locations

✅ Streamlined citizen issue reporting

✅ Created centralized sanitation management workflows

---

# 🔮 Future Scope

### RFID-Based Access Management

Enable smart access control and accurate usage tracking.

### Smart Paid Public Toilets

Support digital payments and sustainable maintenance funding.

### Automated Flush Management

Improve hygiene while reducing water wastage.

### Predictive Maintenance

Use advanced AI models to forecast cleaning requirements before issues occur.

### Smart City Integration

Deploy centralized monitoring across city-wide public infrastructure systems.

---

# 🖼️ Screenshots


## Janitor Mobile Application

https://drive.google.com/drive/folders/1bGv6ivX0Mit-nLNVZ4sPT30yS4SmTcWw?usp=sharing

---

# 🔗 Links

### Live Demo

https://sanitrax-user-site.vercel.app/


---

# 🏆 Hackathon Recognition

**HackGenX 2026**

* Team: ThreeBits
* Working MVP Developed
* Successfully Shortlisted
* AI + IoT + Cloud-Based Solution

---

### Building Smarter, Cleaner, and More Accountable Public Sanitation Infrastructure.
