# 🛡️ GigShield AI – Insurance for Gig Workers

---

## 📌 Problem

Delivery workers on platforms like Swiggy and Zomato face frequent income loss due to external disruptions such as heavy rain, floods, and high pollution levels. These events can reduce their working hours by 20–30%, yet they currently have no financial safety net.

---

## 💡 Solution

GigShield AI is an AI-powered parametric insurance platform that automatically compensates delivery workers for income loss caused by external disruptions.

GigShield AI leverages parametric insurance principles, where payouts are triggered by predefined external data conditions rather than manual claim verification.

---

## 👤 Target Persona

- Food Delivery Workers (Swiggy / Zomato)
- Urban gig workers dependent on daily earnings
- Highly affected by environmental disruptions

---

## ⚙️ Key Features

- 📅 Weekly Insurance Pricing Model  
- 🤖 AI-Based Risk Prediction  
- 🌧️ Real-Time Disruption Monitoring  
- ⚡ Automatic Claim Triggering  
- 💸 Instant Payout (simulated via Razorpay sandbox)

---

## 💰 Weekly Premium Model

GigShield AI follows a weekly pricing strategy aligned with gig workers’ earning cycles.

Premium is dynamically calculated using:
- Location-based risk (flood-prone / pollution-heavy zones)
- Historical weather data
- Worker activity patterns

👉 Example:
- Low-risk zone → ₹15/week  
- High-risk zone → ₹30/week  

---

## 🌩️ Parametric Triggers (Automatic Claims)

Claims are triggered when predefined thresholds are met:

- 🌧️ Heavy Rainfall (e.g., > 50 mm/day)
- 🌊 Flood Alerts in region
- 🌫️ High Pollution (AQI > 300)
- 🚫 Zone Inaccessibility (simulated)

These triggers eliminate manual claim filing and ensure instant payouts.

---

## 🤖 AI/ML Integration

GigShield AI integrates AI at multiple stages:

- Risk Prediction Model: Estimates probability of disruptions  
- Dynamic Pricing Model: Adjusts weekly premium  
- Fraud Detection Model: Identifies suspicious claim patterns  

---

## 🚨 Adversarial Defense & Anti-Spoofing Strategy

To prevent large-scale fraud (e.g., GPS spoofing attacks), GigShield AI uses a multi-layered defense system:

### 🔒 Multi-Signal Location Verification
- GPS + Network (WiFi/Cell Tower) validation  
- Sensor-based movement tracking (accelerometer, gyroscope)  
- Detection of unrealistic location jumps  

### 📊 Behavioral Analysis
- Identifies abnormal activity patterns  
- Flags unrealistic delivery efficiency  
- Detects repeated claim behavior  

### 🕸️ Fraud Ring Detection
- Same device fingerprint  
- Same IP/VPN  
- Synchronized activity  

### ⚖️ Risk Scoring System
- Low Risk → Normal operation  
- Medium Risk → Additional verification  
- High Risk → Claim review / payout restriction  

### 🧍 Protecting Genuine Users
- No penalties for single anomalies  
- Multi-signal validation before flagging  
- Appeal and manual review system  

👉 Core Principle:  
GigShield AI uses a probabilistic trust model instead of relying on a single data source like GPS.

---

## 🔄 System Workflow

1. User registers on the platform  
2. AI calculates weekly premium  
3. System continuously monitors external conditions  
4. Disruption detected via APIs  
5. Claim triggered automatically  
6. Instant payout processed  

---

## 🏗️ High-Level Architecture

User → Web App (React) → Backend (Node.js)  
→ AI Engine (Python ML Models)  
→ External APIs (Weather, Pollution)  
→ Trigger Engine → Payout System (Razorpay Sandbox)

---

## 🛠️ Tech Stack

- Frontend: React  
- Backend: Node.js  
- Database: MongoDB  
- AI/ML: Python (Scikit-learn)  
- APIs: OpenWeatherMap API  
- Payments: Razorpay Sandbox  

---

## 📊 Business Impact

- Reduces financial uncertainty for gig workers  
- Minimizes fraudulent claims using AI-driven validation  
- Enables scalable, low-cost insurance  

---

## 🧪 Development Plan

- Phase 2: Build core platform (registration, pricing, claims)  
- Phase 3: Advanced fraud detection, analytics dashboard, scaling  

---

## 🎯 Vision

To create a financial safety net for gig workers, ensuring they are protected against unpredictable environmental disruptions through automation, AI, and fair risk assessment.
