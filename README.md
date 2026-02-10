# Meta Lead Quality Feedback Pipeline Dashboard

## 🎯 Overview

An **enterprise-grade automated system** that solves the critical problem of poor lead quality from Meta Ads by creating a continuous feedback loop between lead performance data and Meta's targeting algorithm. Built as a **full-time employee at a Mumbai-based PropTech startup** (channel partner firm) to bridge the massive quality gap between Meta and Google Ads leads in the Indian Real Estate market.



https://github.com/user-attachments/assets/af7b5773-f6c0-4444-9936-6f214dc68c98


## 🔥 The Problem

**Pain Points We Were Facing:**

- Meta Ads generated **60% lower quality leads** compared to Google Ads despite similar spend
- Sales team wasted **4-5 hours daily** chasing unqualified prospects (wrong budget, no intent, fake numbers)
- **₹3.5L+ monthly ad spend** on Meta with poor conversion (18% vs Google's 34%)
- No visibility into **why** certain leads converted while others didn't
- Meta's algorithm had **zero feedback** on lead quality post-click
- Marketing couldn't optimize campaigns beyond basic metrics (CTR, CPL)
- Massive disconnect between **marketing metrics** (volume) and **sales reality** (quality)



## ✅ The Solution

A smart feedback loop system that **teaches Meta what a "good lead" looks like** by:

1. **Capturing** every lead interaction across channels (forms, calls, emails, site behavior)
2. **Scoring** lead quality using AI + sales team input (0-100 scale)
3. **Sending quality scores back to Meta** via Conversions API in real-time
4. **Refining Meta's targeting** to prioritize high-quality audience patterns
5. **Optimizing budgets** toward campaigns generating better leads

> Think of it as giving Meta a report card for every lead it sends, so it gets smarter over time.



## 📊 Quality Scoring System

We built a **comprehensive 8-factor scoring model** that combines:

### Automated Signals (80% weight)
- **Email engagement** - Opens, clicks, response times
- **Profile completeness** - Form data quality, contact validity
- **Response speed** - How quickly they engage after inquiry
- **Budget alignment** - Stated budget vs property prices
- **Demographics fit** - Age, location, family size match
- **Behavioral intent** - Site visits, brochure downloads, time spent
- **Location relevance** - Proximity to property, commute feasibility
- **Purchase timeline** - Urgency indicators, lease expiration dates

### Sales Team Feedback (20% weight) ⭐
After first contact, sales reps provide a **1-5 rating**:
- **5 (Excellent)**: Ready to buy, budget confirmed, decision-maker engaged
- **4 (Good)**: Genuine interest, realistic timeline
- **3 (Average)**: Needs nurturing, timeline uncertain
- **2 (Poor)**: Low engagement, budget mismatch
- **1 (Bad)**: Fake info, no intent, time-waster

**Final Score Formula:**  

Quality Score = (Automated Factors × 0.80) + (Sales Rating × 0.20)




## 🔁 How The Feedback Loop Works

1. **Lead comes in** from Meta Ads → Instant automated scoring (0-100)
2. **Sales team contacts** lead → Adds human quality rating (1-5)
3. **Quality score sent to Meta** via Conversions API with tags:
   - Score value, sales rating, budget range, property interest
   - High-quality leads (70+) flagged as "HighValueLead" event
   - Low-quality leads (<40) sent as negative signal
4. **Meta's algorithm learns** which audience traits = quality leads
5. **Targeting auto-adjusts** - Lookalike audiences refined, poor patterns excluded
6. **Campaigns optimize** - Budget flows to high-performing ad sets

This cycle repeats **every single day**, creating compound improvements.



## 📈 Key Metrics & Results

### 30-Day Impact After Launch

#### Quality Improvements:
- Average Lead Quality Score: **58 → 73** (+26%)
- High-Quality Lead %: **22% → 38%** (+73%)
- Sales Team Rating: **2.8 → 3.9** (+39%)

#### Conversion Performance:
- Meta Conversion Rate: **18.4% → 27.8%** (+51%)
- Quality Gap to Google: **15.8% → 6.4%** (narrowed by 60%)
- Cost Per Quality Lead: **₹3,200 → ₹2,450** (-23%)

#### Business Impact:
- Same ₹5L monthly spend → **+58% more quality leads** (156 → 247)
- Sales Closed: **+82%** (28 → 51 deals/month)
- Additional Revenue: **₹1.2Cr/month**
- ROAS: **240% → 485%** (+102% improvement)

#### System Performance:
- **2,847 feedback events/day** sent to Meta
- **98.7% API success rate**
- **47 optimization cycles** completed
- **99.8% uptime**



## 🎨 Dashboard Features

### Real-Time Monitoring:
- Live lead queue with quality badges (Green/Orange/Red)
- Auto-refresh every 30 seconds
- Pulsing status indicators showing active pipeline
- New lead alerts with slide-in animations

### Visual Analytics:
- Quality distribution donut chart
- 8-factor breakdown bars
- 30-day trend lines (Meta vs Google)
- Conversion funnel comparison
- 7-day sparklines on metric cards

### AI Recommendations:
- Priority-ranked optimization suggestions
- Predicted impact forecasts
- One-click campaign adjustments
- A/B testing status tracking

### Design:
- Glass morphism cards on deep space blue background
- Gradient accents (indigo to purple)
- Color-coded metrics (green/orange/red)
- Smooth hover effects and transitions
- Fully responsive (desktop/tablet/mobile)



## 🔌 Tech Stack

| Category | Technologies |
|----------|-------------|
| **Frontend** | React, Recharts, Tailwind CSS |
| **Backend** | Node.js, Express |
| **Database** | PostgreSQL |
| **APIs** | Meta Conversions API, CRM integration |
| **Deployment** | Cloud-hosted, auto-scaling |



## 💡 Why This Matters

**Before this system:** Marketing optimized for **cheap leads**, Sales dealt with the **quality problem**.

**After this system:** Marketing and Sales **aligned on quality**, Meta learns what actually converts, budget stops getting wasted.

The breakthrough was **closing the feedback loop** - most companies track conversions but never tell ad platforms *which leads were actually good*. This dashboard makes lead quality a first-class metric that drives algorithmic improvement.


<div align="center">

**Built with ❤️ for the Indian Real Estate market**

</div>
