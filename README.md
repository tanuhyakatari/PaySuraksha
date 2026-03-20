# PaySuraksha
Because every day’s income matters.

🧠 Inspiration:
India’s gig economy runs on millions of delivery partners who work daily under unpredictable conditions. A sudden downpour, extreme pollution, or unexpected curfew can instantly halt their work, cutting off their income for the day.

We realized a critical gap:
While platforms depend on gig workers, workers themselves have no protection against income loss.

PaySuraksha was born to bridge this gap — ensuring that even when work stops, income doesn’t.

❗ Problem Statement:
Delivery partners (Swiggy, Zomato, Zepto, Amazon, etc.) lose 20–30% of their income due to external disruptions such as:

Heavy rainfall

Floods

High pollution

Local restrictions or curfews

Currently, there is no real-time, automated insurance system that compensates for these income losses.

💡 What It Does

PaySuraksha is a parametric insurance platform that:

Monitors real-time environmental and social conditions

Automatically detects disruptions affecting work

Triggers claims without manual intervention

Processes payouts for lost income instantly

Prevents fraudulent claims using intelligent verification systems

👉 It acts as a financial safety net for gig workers, ensuring income continuity.

👤 Target Users

Food delivery partners (Swiggy, Zomato)

Grocery delivery workers (Zepto, Blinkit)

E-commerce delivery agents (Amazon, Flipkart)

These workers rely on daily earnings, making them highly vulnerable to disruptions.

⚙️ How It Works (Workflow)

User Onboarding
Delivery partner registers with basic details

Risk Profiling
System evaluates location-based risks using historical data

Weekly Premium Assignment
A dynamic premium is calculated based on risk level

Real-Time Monitoring
Continuous tracking of:

Weather conditions

Pollution levels

Local disruptions

Parametric Trigger Activation
If thresholds are exceeded → claim is automatically triggered

Verification Layer
System validates authenticity using behavioral and device data

Instant Payout
Verified claims are processed immediately

💰 Weekly Pricing Model

PaySuraksha uses a weekly subscription model, aligned with gig workers’ income cycles.

Risk Level	Weekly Premium
Low Risk	₹20/week
Medium Risk	₹35/week
High Risk	₹50/week

Premiums are dynamically adjusted based on:

Environmental risk patterns

Location history

Worker activity trends

⚡ Parametric Triggers

Claims are automatically triggered when:

🌧️ Rainfall exceeds threshold

🌫️ AQI crosses unsafe levels

🌊 Flood alerts are issued

🚧 Curfews or restrictions are imposed

📉 Platform outages occur

👉 No paperwork. No delays. Fully automated.

🤖 Intelligent System Design

PaySuraksha integrates intelligent systems for:

Risk Prediction

Identifies high-risk zones

Forecasts disruption probability

Dynamic Pricing

Adjusts premiums based on real-time risk

Claim Automation

Eliminates manual claim filing

Fraud Detection

Detects anomalies and suspicious claims

🔐 Adversarial Defense & Anti-Spoofing Strategy

🚨 Challenge: Fraudsters using GPS spoofing to trigger false claims

1. Differentiation: Real vs Fake Users

PaySuraksha does not rely solely on GPS.
Instead, it analyzes behavioral patterns such as:

Movement consistency

Route patterns

Activity levels

👉 Real workers show natural movement
👉 Spoofers show static or unrealistic behavior

2. Multi-Layer Data Analysis

To strengthen verification, the system analyzes:

📱 Device motion data (accelerometer)

📊 App usage patterns

🔋 Battery behavior

📶 Network signal changes

📍 Route consistency

⏱️ Active vs idle time

3. Fraud Ring Detection

To counter coordinated attacks:

Detects clusters of users at identical fake locations

Identifies synchronized claim patterns

Flags similar behavioral signatures across multiple users

👉 Enables detection of fraud networks, not just individuals

4. Trust-Based Verification System

To ensure fairness:

Trust Level	System Action
High	Instant payout
Medium	Delayed verification
Low	Manual review

👉 Prevents fraud while protecting genuine users

🧰 Tech Stack

Frontend: React / HTML, CSS

Backend: Node.js / Spring Boot

Data Processing: Python

Database: MongoDB / MySQL

APIs: Weather APIs, Traffic data (mock)

Payments: Razorpay / Stripe (sandbox)

🚧 Challenges We Ran Into

Designing a system resilient to GPS spoofing

Balancing fraud prevention with user fairness

Creating a realistic weekly pricing model

🏆 Accomplishments

Built a fraud-resistant insurance architecture

Designed a behavior-based verification system

Created a scalable model tailored for gig workers

📚 What We Learned

Real-world systems must handle adversarial behavior

Automation must be balanced with trust

Simplicity in UX is critical for adoption

🔮 What’s Next

Integrate real-time APIs

Develop full-stack implementation

Simulate live claim processing

Enhance fraud detection models

🔗 Links

🚀 Try It Out: (Add your Figma/Prototype link here)

💻 GitHub Repository: (Add your repo link here)

🎥 Demo Video: (Add your video link here)
