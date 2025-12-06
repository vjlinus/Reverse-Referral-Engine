# <img width="24" height="24" alt="image" src="https://github.com/user-attachments/assets/354ad245-bb6d-4994-878d-6c1f17d8db61" />  Reverse Referral Engine

**Automated Client Satisfaction Tracking & Referral Request System**

![Zapier](https://img.shields.io/badge/Zapier--FF4A00?logo=zapier)
![Status](https://img.shields.io/badge/Status-Production%20Ready-success)


---

## 📋 Overview

The **Reverse Referral Engine** is a unique Zapier-based automation system that detects micro-moments of client satisfaction—positive emails, and automatically requests referrals only when clients are happiest. 

Unlike traditional lead generation workflows, this is a **defensive sales automation** that monitors existing client relationships and triggers revenue opportunities based on sentiment analysis.

---

## 🎥 How It Works

```
Client sends positive email → Happiness score +5 → Score reaches 25 → 
Wait 1 day → Send personalized referral request → Reset score
```


## <img width="27" height="27" alt="image" src="https://github.com/user-attachments/assets/09fbcbcc-cac1-4e10-83a2-6825d8828202" /> Key Insight: 
Most businesses ask for referrals randomly or never ask at all. Asks for referrals at peak client satisfaction, not randomly.

---

## ✨ Features

- ✅ **Automatic sentiment detection** from client emails
- ✅ **Happiness score tracking** for each client
- ✅ **Smart timing** with 24-hour delay before asking
- ✅ **Spam prevention** - clients asked only once
- ✅ **Complete audit trail** in Google Sheets
- ✅ **100% free** - no paid APIs required
- ✅ **Scalable** from 1 to 1000 account managers

- ## 🎓 Use Cases

### Small Agencies
Manage happiness scores for multiple account managers.

### SaaS Customer Success
Monitor client health scores and trigger expansion conversations.

### B2B Sales Teams
Track account satisfaction and identify upsell opportunities.

## 📈 Results

### Expected Outcomes

**For Enterprises (500 clients, 10 AMs):**
- 80-120 referrals annually
- $4-6M potential pipeline value
- Consistent process across team

---

## 🌐 AI Referral Enginer Workflow 

### 🎪 Interactive Workflow Canvas
**[View Live Workflow →](https://zapier.com/app/canvas/public/01ae7cd3-b02f-4de0-9728-34519874a207)**

*Interactive canvas showcasing AI-powered referral engine workflows*
         └──────────────────────┘
```

# 🔒 Privacy & Compliance

- No external APIs or data sharing
- Client data stored in your Zapier tables 
- GDPR compliant (data under your control)
- No PII exposed to third parties

- ## 📊 Data Model

### Zapier Table: "Client Happiness Tracker"

| Field Name | Type | Description |
|------------|------|-------------|
| `Client Name` | Text | Client/company name |
| `Client Email` | Email | Primary contact email |
| `Current Happiness Score` | Number | Accumulated satisfaction points |
| `Last Score Update Date` | Date | Most recent score change |
| `Last Referral Request Date` | Date | When we last asked for referral |
| `Total Referrals Given` | Number | Count of referrals from this client |
| `Notes` | Text | Additional context |

### Zapier Database: "Referral Log"

| Column | Description |
|--------|-------------|
| Date | Timestamp of event |
| Client Name | Who triggered the event |
| Trigger Type | "Positive Email" or "Referral Request Sent" |
| Score Before | Happiness score before update |
| Score After | Happiness score after update |
| Referral Requested | Yes/No |
| Referrals Received | Count |

## 📎 Author
**Jason Linus**  
Automation & GTM Engineer  
[https://www.linkedin.com/in/jason-linus-7120a51/] | [Portfolio](https://nifty-yak-ffd.notion.site/Jason-Linus-8c81e08090a74a9ca2d20287693bebe9?pvs=74)
