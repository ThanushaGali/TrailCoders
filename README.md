# GigShield - AI Powered Weekly Income Protection for Quick Commerce Delivery Workers

## 👥 Team Details
- Team Name: TrailCoders
- Members:
  - Thanusha Gali
  - Soumika Devarakonda
  - Lyuthika Pode
  - Vasavi Pinnam
  - Olivia Mallampalli
 
## 🎥 Video
[Watch Here](video-link)

## 📌 Problem Statement

Quick commerce delivery partners working with platforms like Zepto, Blinkit, and Instamart operate in highly time-sensitive and hyperlocal environments. Their income is directly dependent on continuous order flow within small delivery zones.

However, external disruptions such as heavy rain, waterlogging, extreme heat, pollution, and zone shutdowns can instantly reduce or completely stop deliveries. As a result, workers lose 20–30% of their weekly income, with no financial protection.

Currently, there is no system that compensates for income loss caused by such uncontrollable events.

## 👤 Target Persona

Quick Commerce Delivery Partner (Zepto/Blinkit/Instamart)

Works in a 2–5 km delivery radius

Delivers orders within 10–20 minutes

Earns based on number of completed deliveries

Highly dependent on peak hours and zone activity

Faces frequent income loss due to micro-level disruptions

## 💡 Proposed Solution

GigShield is an AI-powered parametric insurance platform that provides automatic income protection for delivery workers.

Unlike traditional insurance:

- No manual claim process

- No paperwork

- No waiting time

The system:

- Monitors real-time conditions

- Detects disruptions automatically

- Triggers instant payouts

## 🚀 Why GigShield Stands Out

- Hyperlocal Zone Intelligence
  Detects disruptions at a micro-zone level (2–3 km), ensuring accurate identification of localized issues like waterlogging or traffic congestion.

- Income-Based Dynamic Payout
  Calculates expected earnings and compensates actual income loss instead of offering fixed payouts.

- Zero-Touch Claim System 
  Fully automated process — no manual claims, instant detection, validation, and payout.

- Smart Trust Score Fraud Detection
  Uses location consistency, activity patterns, and claim history to prevent fraudulent claims.

### Trust Score-Based Fraud Detection

Each user is assigned a dynamic trust score based on:

- Location consistency

- Activity patterns

- Claim history

This ensures intelligent fraud prevention.

## ⚙️ System Workflow

```
User Onboarding
      ↓
AI Risk Profiling & Pricing
      ↓
Weekly Policy Activation
      ↓
Real-Time Monitoring (Weather, AQI, Orders)
      ↓
Disruption Detection (Zone-Level)
      ↓
Automatic Claim Trigger
      ↓
Fraud Validation (Trust Score + GPS)
      ↓
Instant Payout (UPI)
```

## 💰 Weekly Pricing Model

GigShield follows a weekly subscription model aligned with gig worker earnings.

```
User Data (Location + Activity)
↓
Base Premium (₹20/week)
↓
Risk Adjustments
(Flood +₹5 | Pollution +₹3 | Traffic +₹2)
↓
AI Pricing Engine
(Weather + History + Patterns)
↓
Final Premium (₹25–₹35/week)
↓
Coverage Allocation
(₹500 – ₹1500/week)

```

## ⚡ Parametric Triggers

GigShield uses predefined measurable triggers:

| Disruption | Condition | Action |
|-----------|----------|--------|
| Heavy Rain | Rainfall > 50mm | Auto payout |
| HeatWave | Temperature > 42C | Auto payout |
| Order Drop |  < 40% normal orders | Auto payout |
| Pollution | AQI > 300 | Auto payout |
| Zone Shutdown | No activity in Zpne | Auto payout |

## 🤖 AI/ML Integration

1. Risk Assessment Model

   Predicts disruption probability

   Inputs: location, weather, historical data

2. Dynamic Pricing Engine

   Adjusts weekly premium

   Based on predicted risk

3. Income Prediction Model 

   Estimates expected earnings

   Calculates actual income loss

4. Fraud Detection System

   Detects anomalies using ML

   Prevents misuse and fake claims

## 🛡️ Fraud Detection Strategy

GPS location validation

Activity consistency checks

Duplicate claim prevention

Trust score evaluation

Anomaly detection (ML-based)

## 🔗 Integration Plan

Weather API (OpenWeather)

AQI API (pollution data)

Traffic data 

Delivery platform simulation

Payment gateway (Razorpay test)

## 🛡️ Adversarial Defense & Anti-Spoofing Strategy  

To counter advanced GPS spoofing and coordinated fraud attacks, GigShield uses a **multi-layered behavioral intelligence system**.

### 🔍 Differentiation (Real vs Fake)
- Movement pattern vs static spoofed location  
- Delivery activity validation  
- Behavioral consistency analysis  

### 📊 Data Signals Used
- GPS trajectory (not just location)  
- Order activity & timestamps  
- App usage patterns  
- Network anomalies  
- Zone-level disruption correlation  

### 🤖 AI Defense
- Anomaly detection (Isolation Forest)  
- Dynamic **Trust Score system**  
- Fraud pattern recognition  

### ⚖️ UX Balance
- Auto-approved (high trust)  
- Soft verification (medium risk)  
- Rejected (high fraud probability)  

### 🧠 Anti-Collusion Detection
- Detects clustered fake claims  
- Identifies synchronized behavior  
- Monitors sudden spike in same zone  

Prevents large-scale fraud attacks like coordinated spoofing rings  

## 🧭 Customer Journey
```
Awareness
      ↓
Onboarding
      ↓
AI Profiling
      ↓
Plan Selection
      ↓
Activation
      ↓
Monitoring
      ↓
Disruption
      ↓
Auto Claim
      ↓
Payout
      ↓
Dashboard

```

## 🧱Tech Stack

Frontend: React.js

Backend: Node.js, Express.js

Database: MongoDB

AI/ML: Python, Flask/FastAPI, scikit-learn

APIs: OpenWeather API, AQI API, Traffic API 

Monitoring: Cron Jobs / Scheduler

Payment: Razorpay (Test Mode) 

Tools: GitHub, Postman, VS Code

## 🎯 Conclusion

GigShield transforms traditional insurance into a proactive, AI-driven income protection system for quick commerce delivery workers.

By leveraging hyperlocal risk analysis, real-time monitoring, and a zero-touch claim process, the platform ensures instant financial support during unexpected disruptions.

With a simple weekly pricing model and intelligent fraud detection, GigShield provides a reliable and scalable solution to protect the livelihoods of gig workers in an unpredictable environment.
