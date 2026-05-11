# NexTrack Pro | Intelligent Financial Dashboard 💎

NexTrack Pro is a high-performance, mobile-first expense management system built with a focus on **Data Analytics Mastery** and **Native-Feel User Experience**. This project demonstrates advanced JavaScript logic, state persistence, and responsive UI engineering.

## 🚀Live Demo
https://tazhalli5.github.io/NexTrack-Pro/

## 🚀 Key Features

* **Dynamic Onboarding:** A personalized user setup flow that initializes the dashboard based on user identity and custom budget limits.
* **Array Methods Mastery:** Real-time data processing using ES6+ functional programming (`.reduce()`, `.filter()`, and `.map()`) for instant analytics.
* **Adaptive Budget Health:** A reactive UI that shifts color states (Stable → Warning → Critical) and triggers haptic feedback based on spending velocity.
* **Smart Search & Filtering:** Instant history retrieval using high-speed array filtering.
* **Native Mobile UX:** Features a gesture-inspired Bottom Sheet for data entry, haptic vibration alerts, and optimized touch targets.

## 🛠️ Technical Stack

* **Frontend:** HTML5, Tailwind CSS (Utility-first styling)
* **Logic:** JavaScript ES6+ (Array Mastery, LocalStorage API)
* **Charts:** Chart.js (Interactive Data Visualization)
* **Icons:** Localized Indian Iconography (🛺, 🍱)

## 🧠 Core JavaScript Concepts Implemented

### Data Aggregation (.reduce)
The application avoids heavy loops by using `.reduce()` to calculate total expenditures and group category totals in a single pass:
```javascript
const total = history.reduce((sum, item) => sum + item.amount, 0);
