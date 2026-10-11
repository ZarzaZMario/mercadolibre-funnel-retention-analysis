E-commerce conversion funnel and cohort retention analysis across LATAM markets for MercadoLibre (2025).
# 🛒 E-Commerce Funnel & Cohort Retention Analysis (MercadoLibre 2025)

![Excel](https://img.shields.io/badge/Excel-Data_Analysis-217346?style=for-the-badge&logo=microsoft-excel&logoColor=white)
![CRO](https://img.shields.io/badge/CRO-Conversion_Optimization-FF6F00?style=for-the-badge)
![Retention](https://img.shields.io/badge/Analytics-Cohort_Retention-00838F?style=for-the-badge)

## 📌 Executive Summary

### Context & Objective
This project analyzes user behavior across key e-commerce conversion funnel stages and user retention cohorts for MercadoLibre across 10 LATAM countries (Jan 2025 – Aug 2025). The goal is to identify points of friction, drop-offs, and user churn to guide Conversion Rate Optimization (CRO) and product retention strategies.

**Key Funnel Metrics Analyzed:**
- `select_item` (Catalog Exploration) → `add_to_cart` (Cart Addition)
- `begin_checkout` → `add_shipping_info` → `add_payment_info` → `purchase`

---

## 📊 Key Findings

### 1. Conversion Funnel Bottlenecks
- **Major Friction Point (`add_to_cart`):** The largest drop occurs between item selection (76.90%) and cart addition (11.01%), representing a relative loss of ~85.7% of users.
- **Checkout Abandonment:** Final overall conversion rate drops to 1.25%.
- **Regional Disparities:**
  - **Top Performers:** Uruguay (4.55%), Bolivia (3.23%), and Mexico (2.48%) lead in final purchase conversion.
  - **Critical Technical Leaks:** 
    - **Paraguay:** 0% conversion at `begin_checkout` (total drop-off indicating an interface or tracking event failure).
    - **Ecuador & Colombia:** 0% final conversion due to complete drop-off during the payment phase (`add_payment_info` → `purchase`).

### 2. User Retention Dynamics (Cohorts)
- **Retention Curve:** Overall user retention decays progressively from 86.6% (D7) to 2.6% (D28).
- **Strongest Cohort:** March 2025 cohort recorded the highest retention (87.7% D7 / 3.0% D28).
- **Country Highlights:** Brazil (87.2% D7) and Mexico (86.1% D7) exhibit strong initial user engagement, while Peru (3.2%) and Mexico (3.1%) maintain the highest D28 long-term retention.

---

## 🎯 Strategic Recommendations

1. **UX & Product Page Optimization:**
   - Redesign product detail pages and Call-to-Action (CTA) buttons ("Add to Cart") to reduce the initial 85.7% drop.
   - Disclose shipping costs transparently early in the funnel to prevent cart abandonment.
2. **Technical Audits:**
   - Execute urgent technical audits on event tracking and UI flows in Paraguay (`begin_checkout`) and payment gateway integration in Ecuador and Colombia.
3. **Targeted Retention Strategies:**
   - **Early Onboarding (D1–D7):** Strengthen initial user activation in Ecuador and Bolivia to prevent steep D7 churn.
   - **Re-engagement Campaigns (D10–D18):** Deploy targeted push notifications and special offers in Colombia and Chile to prevent late-stage drop-off before D28.

---

## 📁 Repository Structure

```text
├── data/
│   └── MercadoLibre_Funnel_Retention_Summary.xlsx
└── README.md
