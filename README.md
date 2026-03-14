Kavach AI: Hyper-Local Parametric Insurance for Food Delivery Workers 🛡️

Protecting the income of India’s delivery partners through automated disruption detection and intelligent risk modeling.

🎯 Core Strategy: The Kavach Mission

Kavach AI is designed to protect platform-based food delivery workers from sudden income loss caused by external disruptions such as extreme weather or environmental hazards.

Food delivery partners rely heavily on peak hours to earn their daily income. When unexpected disruptions like heavy rain, flooding, or severe pollution occur, delivery operations slow down or completely stop. This leads to immediate income loss for workers.

Kavach AI introduces a parametric insurance system that automatically detects these disruptions and triggers compensation for affected workers without requiring manual claims.

Key principles of the Kavach platform:

• Persona Focus: Food delivery partners working on platforms like Swiggy and Zomato
• Income Protection Only: Coverage is strictly limited to loss of working hours and income
• Weekly Pricing Model: Insurance plans are structured around a weekly cycle that aligns with gig worker earnings patterns
• Automated Claims: Disruption detection automatically initiates claims and payout processing

The goal is to provide a fast, reliable safety net that protects gig workers from unavoidable environmental disruptions.

👤 Persona-Based Scenario & Workflow
Target Persona: “The Rain-Interrupted Rider”

Name: Arjun
Role: Food delivery partner for a major food delivery platform.

Arjun typically earns most of his income during lunch and dinner peak hours. One evening, a sudden heavy rainstorm floods roads in his delivery zone. Restaurants temporarily stop dispatching orders, and deliveries drop drastically.

Arjun loses several hours of potential earnings during the busiest part of the day.

Kavach AI detects this disruption automatically and compensates him for the lost income.

Application Workflow

Worker Onboarding

Arjun registers on the Kavach platform and provides:

• Name and contact details
• Delivery platform (Swiggy/Zomato)
• Operating city and zone
• Estimated weekly income

The system uses this information to create a risk profile.

Risk Assessment

Kavach calculates a weekly insurance premium based on:

• Worker income level
• Geographic risk of disruptions
• Environmental risk indicators for the delivery zone

Disruption Monitoring

The Kavach backend continuously monitors disruption signals such as:

• Weather data (rainfall intensity)
• Air quality levels
• Local disruption indicators

These signals are retrieved from external APIs or simulated data sources.

Parametric Trigger

If rainfall intensity exceeds a predefined threshold (for example 15mm per hour) in Arjun’s delivery zone, the system recognizes that delivery activity is likely disrupted.

Automatic Claim Initiation

Once the disruption condition is satisfied:

• The system checks if the worker has an active policy
• Validates the worker’s registered location
• Estimates potential income loss during the disruption window

A claim is automatically generated without requiring manual action from the worker.

Payout Simulation

The system simulates an instant payout through a mock payment service.

The worker dashboard updates to show:

• Claim status
• Estimated income compensation
• Payout confirmation

💰 Weekly Pricing Model & Parametric Triggers

Gig workers typically operate on short earning cycles. Therefore, Kavach AI uses a weekly premium structure to keep coverage simple and affordable.

Dynamic Weekly Premium

The premium is calculated using a risk-adjusted formula based on worker income and environmental risk levels.

Example structure:

Weekly Premium = Base Premium + Zone Risk Adjustment − Loyalty Discount

Where:

• Base Premium is derived from the worker’s average weekly income
• Zone Risk Adjustment increases premiums in high-risk areas prone to frequent disruptions
• Loyalty Discount reduces premiums for workers with consistent usage and low claim history

Parametric Disruption Triggers

The system automatically triggers claims when predefined conditions are detected.

Environmental triggers may include:

• Heavy Rainfall exceeding a defined threshold
• Extreme Heat conditions affecting outdoor work
• Severe Air Pollution levels impacting mobility

Social disruption triggers may include:

• Local curfews
• Sudden market closures
• Restricted movement zones

These triggers represent external factors that prevent delivery work from continuing, leading to income loss.

🤖 Intelligent System Logic

Although Kavach AI focuses on automation rather than complex ML infrastructure, it incorporates intelligent logic to support risk assessment and fraud prevention.

Risk-Based Premium Calculation

The platform analyzes historical disruption patterns for a worker’s delivery zone and adjusts the weekly premium accordingly.

Areas with frequent environmental disruptions are categorized as higher risk and receive slightly higher premiums.

Fraud Detection Mechanisms

To ensure system integrity, Kavach includes basic fraud detection safeguards such as:

• Location validation to confirm the worker operates in the affected zone
• Duplicate claim prevention for the same disruption event
• Policy verification before claim approval

These checks prevent misuse while maintaining a seamless experience for legitimate users.

🏗️ Technology Stack & Development Plan
Technology Stack

Frontend
React + TailwindCSS for a responsive web interface

Backend
Node.js with Express for API development and business logic

Database
MongoDB with Mongoose for storing workers, policies, and claims

Integration APIs
Weather data APIs or simulated disruption services for event detection

Payment System
Mock payout service to simulate compensation transactions

6-Week Development Roadmap
Phase 1 – Ideation & Foundation

Focus on defining the persona, application workflow, and system architecture.
Initial prototype screens and project repository setup are completed during this phase.

Phase 2 – Automation & Protection

Core system functionality is implemented including:

• Worker registration
• Policy creation and management
• Dynamic premium calculation
• Automated disruption triggers
• Claim generation

Phase 3 – Scale & Optimization

Final improvements focus on platform reliability and usability.

This phase includes:

• Fraud detection mechanisms
• Payout simulation
• Worker and admin dashboards
• Final demonstration of disruption detection, automated claim generation, and payout workflow.
