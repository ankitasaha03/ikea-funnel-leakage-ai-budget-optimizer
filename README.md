# ikea-funnel-leakage-ai-budget-optimizer
LIVE DASHBOARD-http://localhost:5173/
AI-powered omnichannel marketing analytics dashboard for IKEA that identifies funnel leakage, applies Markov Chain attribution and Hill saturation modeling, and optimizes campaign budgets using SLSQP.
# IKEA Funnel Leakage & AI Budget Optimization Engine

## IKEA Growth AI – Omnichannel Touchpoint Attribution & Friction Minimization

An AI-powered omnichannel marketing analytics and budget optimization dashboard designed to identify customer funnel leakage, evaluate marketing channel effectiveness, perform multi-touch attribution, model diminishing returns and optimize campaign budget allocation.

---

## 🚀 Project Overview

The IKEA Funnel Leakage & AI Budget Optimization Engine combines customer journey analytics, marketing attribution and optimization techniques into a single decision-support dashboard.

The system analyzes the complete omnichannel customer journey from:

**Awareness → Catalogue Search → 3D Room Planning → Cart → Delivery & Assembly → Payment**

The dashboard identifies where customers are lost, estimates associated leakage, evaluates the contribution of different marketing channels and generates AI-assisted budget allocation recommendations.

---

## 🎯 Business Problem

Organizations invest across multiple marketing channels, but traditional reporting often focuses on:

- Last-click attribution
- Channel-level conversion rates
- Campaign spend
- Overall revenue

These metrics may not fully explain where customers drop out of the journey or which touchpoints influence downstream conversion.

This project addresses the problem by integrating:

- Funnel leakage analysis
- Multi-touch attribution
- Markov Chain removal-effect modeling
- Hill saturation response curves
- SLSQP constrained optimization
- Real-time omnichannel event monitoring

---

## 💡 Key Objectives

1. Identify major customer funnel drop-off points.
2. Estimate monetary leakage across customer journey stages.
3. Measure marketing channel contribution using multi-touch attribution.
4. Identify channels with diminishing returns.
5. Determine optimized campaign spending levels.
6. Minimize funnel leakage.
7. Improve projected marketing ROI.
8. Provide actionable recommendations through an interactive dashboard.

---

# 📊 Dashboard KPIs

The dashboard displays the following major KPIs:

| KPI | Dashboard Value |
|---|---:|
| Top-of-Funnel Qualified Leads | 1,140,000 |
| Total Funnel Value Leakage | $16,452.2K |
| Current Attributed Revenue | $8.39M |
| AI Optimized Projected ROI | 6.54x |
| Delivery & Assembly Drop-off | 74.6% |
| Total Revenue Uplift | +$1,820.0K |
| Avoided Leakage Capital | $120.8K |

> These values represent the outputs displayed by the project dashboard under its configured model assumptions.

---

# 🔍 Core Analytical Components

## 1. Omnichannel Funnel Analysis

The dashboard tracks customer progression across six stages:

1. Impressions & Awareness
2. Qualified Leads & Catalogue Search
3. 3D Room Planner & Saved Layouts
4. Cart Additions & Multi-Item Bundles
5. Delivery & Assembly Surcharge
6. Order Confirmation & Payment

For every stage, the dashboard provides:

- User volume
- Drop-off percentage
- Estimated leakage
- Customer friction point

---

## 2. Channel Leakage Analysis

The project evaluates six marketing channels:

- Social Media Inspiration
- TV & OOH Billboard Campaigns
- IKEA Kreativ AR 3D Room Planner
- Google Shopping & Search Ads
- IKEA Family CRM & Retargeting
- Influencer Room Makeovers

The dashboard compares:

- Marketing spend
- Leads
- Purchases
- Conversion rate
- LTV:CAC
- Leakage cost
- Primary funnel drop-off stage

---

# 🧠 Markov Chain Attribution

The project uses a Markov Chain removal-effect approach to estimate the contribution of marketing touchpoints across the customer journey.

Instead of assigning conversion credit only to the first or last interaction, the model evaluates the impact of removing a particular touchpoint from the journey.

### Example

The dashboard identifies the IKEA Kreativ 3D Room Planner as an important journey component.

The displayed model finding indicates that removing the 3D Room Planner results in a:

**42.8% reduction in overall downstream conversion probability.**

This demonstrates the difference between single-touch attribution and multi-touch attribution.

---

# 📈 Hill Saturation Model

The project uses Hill saturation response curves to model diminishing returns from marketing spend.

The model represents the relationship between:

**Marketing Spend → Expected Revenue**

As spending increases, revenue initially increases rapidly but eventually approaches a saturation point.

This helps identify operating points where additional marketing expenditure produces lower marginal returns.

---

# 🤖 AI Budget Optimization

The dashboard uses constrained optimization through the SLSQP approach.

The optimization considers:

- Total campaign budget
- Drop-off penalty
- Target LTV:CAC
- Minimum spend floor
- Channel response curves
- Predicted revenue

### Displayed optimization configuration

| Parameter | Value |
|---|---:|
| Total Campaign Budget | $850,000 |
| Drop-off Penalty | 1.5x |
| Target LTV:CAC | 3.5x |
| Minimum Spend Floor | $10,000 |

---

# 💰 AI Budget Allocation

The dashboard's optimization engine produces the following displayed allocation:

| Channel | Current Spend | AI Optimal Spend | Reallocation |
|---|---:|---:|---:|
| Social Media Inspiration | $120,000 | $10,000 | -91.7% |
| TV & OOH Billboard Campaigns | $150,000 | $10,000 | -93.3% |
| IKEA Kreativ AR 3D Room Planner | $75,000 | $183,954.31 | +145.3% |
| Google Shopping & Search Ads | $90,000 | $118,537.49 | +31.7% |
| IKEA Family CRM & Retargeting | $35,000 | $167,508.20 | +378.6% |
| Influencer Room Makeovers | $30,000 | $10,000 | -66.7% |

---

# 📊 Channel Performance

| Channel | Conversion Rate | LTV:CAC |
|---|---:|---:|
| Social Media Inspiration | 0.50% | 4.5x |
| TV & OOH | 0.56% | 3.93x |
| IKEA Kreativ AR 3D Room Planner | 2.15% | 64.4x |
| Google Shopping & Search | 1.96% | 44.2x |
| IKEA Family CRM & Retargeting | 4.43% | 339.71x |
| Influencer Room Makeovers | 1.09% | 16.99x |

---

# ⚡ Real-Time Event Monitoring

The dashboard includes a real-time omnichannel journey event stream.

Example events include:

- Assembly surcharge events
- Cart reviews
- 3D Room Planner interactions
- Catalogue search abandonment
- Out-of-stock warehouse alerts

The interface uses live telemetry to connect operational events with customer journey friction.

---

# 🛠️ Technology Stack

### Frontend

- React
- Vite
- JavaScript
- HTML5
- CSS3
- Data Visualization

### Analytics / AI

- Python
- Markov Chain Attribution
- Hill Saturation Modeling
- SLSQP Optimization
- Funnel Analytics
- Revenue Optimization

### Data & Business Analytics

- Customer Journey Analytics
- Marketing Attribution
- LTV:CAC Analysis
- Conversion Analysis
- Budget Optimization
- Leakage Analysis

### Real-Time

- WebSocket
- Live event telemetry

---

# 🏗️ System Architecture

```text
                CUSTOMER JOURNEY DATA
                         │
                         ▼
                DATA PROCESSING LAYER
                         │
                         ▼
              ┌─────────────────────┐
              │ Funnel Analysis     │
              │ Leakage Detection   │
              └──────────┬──────────┘
                         │
          ┌──────────────┼──────────────┐
          ▼              ▼              ▼
     Markov Chain    Hill Model      KPI Engine
     Attribution    Saturation
          │              │
          └──────────────┼──────────────┘
                         ▼
                SLSQP Optimization
                         │
                         ▼
              AI Budget Recommendations
                         │
                         ▼
             Interactive Dashboard
                         │
                         ▼
              Business Decision Support
