# ⚡ GITAM Student Resource Hub

A lightweight, zero-operating-cost web application built specifically for GITAM University students to manage their academics, keep track of attendance requirements, calculate credit-weighted grade points, and access curriculum materials.

## 🚀 Live Link
👉 **[View the Live Web App Here](https://gitam-student-hub.vercel.app)** *(Replace with your actual Vercel production link once deployed)*

---

## 🛠️ Built-In Features

### 1. 📊 GITAM 75% Attendance Planner
* **Smart Buffering Logic:** Automatically calculates whether a student is safe or in an attendance shortage based on actual course inputs.
* **Bunk/Attend Breakdown:** If above 75%, it calculates the exact number of upcoming classes the student can safely skip. If below 75%, it calculates the exact number of consecutive classes required to hit eligibility.

### 2. 🧮 Credit-Based SGPA / CGPA Calculator
* **GITAM Grade Mappings:** Built-in calculation matching the standard letter-to-point configuration ($O = 10$, $A^+ = 9$, $A = 8$, $B^+ = 7$, etc.).
* **Dynamic Terms:** Allows client-side tracking by entering individual course credits and matching targeted grades to find true term aggregates instantly.

### 3. 📚 Subject-Wise Resource Vault (2025-2026 AB)
Curated storefront targeting high-stakes first-year courses for the **2025-2026 Admit Batch**, including:
* **MATH2572** — Discrete Mathematical Structures
* **PHYS1291** — Fundamentals of Engineering Physics
* **24EECE2231** — Foundations of Electrical and Electronics Engineering
* **CHEM1111** — Engineering Chemistry
* **MATH1341** — Calculus and Differential Equations
* **MATH1351** — Trigonometry and Geometry
* **24EECE2211** — Fundamentals of Electrical and Electronics Engineering
* **24EECE2221** — Fundamentals of Sensors and Internet of Things

*Note: Supplementary exam materials for older batches (2018–2024 cohorts) are flagged as **"Coming Soon"** to prevent catalog clutter.*

---

## 💳 Integrated Payment Gateway
* Integrated with **Razorpay Standard Checkout** allowing real-time UPI processing (Google Pay, PhonePe, Paytm, Cards) directly through the frontend client window layer.
* Delivers standard premium exam blueprint packs matching the official GITAM 1.5-hour and 2-hour sessional question patterns.

---

## ⚡ Tech Stack & Hosting Setup (100% Free Tier)
* **Frontend Library:** React.js
* **Backend Framework Bridge:** Supabase JS Client Module
* **Hosting Platform:** Vercel (Integrated directly with GitHub triggers)
* **External Services:** Razorpay API Core Integration Gateway

---

## ⚙️ Environment Configurations
To run this project successfully, ensure you create a `.env` file containing your valid Supabase project variables:

```text
REACT_APP_SUPABASE_URL=your_supabase_project_url
REACT_APP_SUPABASE_ANON_KEY=your_supabase_anonymous_public_key
