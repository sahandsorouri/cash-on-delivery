# 🚚 Cash-on-Delivery Flow Optimization

Redesigned SnappFood's Cash-on-Delivery (COD) experience to reduce failed transactions, increase retention, and minimize fraud — across mobile, web, and logistics ops.

---

## 📌 Overview

- **Company:** SnappFood (Leading F&B eCommerce platform in Iran)
- **Role:** Senior Product Manager – Owned full COD experience across user & courier touchpoints
- **Timeline:** 2-sprint implementation (4 weeks total); rollout to 80K+ merchants
- **Team:** 1 PM (me), 1 UX Designer, 3 Engineers, 1 Ops Lead, 2 Analysts

---

## 🎯 Problem

The legacy COD flow caused:
- High payment refusal at delivery
- Fraudulent orders with fake numbers/addresses
- Courier time wasted on invalid deliveries
- Lack of real-time confirmation for customers

---

## 💡 Solution

Redesigned the COD flow with:
- ✅ **Pre-confirmation prompts** before order submission
- 📩 **SMS fallback + one-tap reconfirmation** for inactive users
- 🔒 **Predictive success scoring** (based on address, history, user type)
- 🛠️ **Courier app fail-safe triggers** (e.g., “no cash received” → auto cancel)
- 🧪 **Feature flag-based rollout** to top 10 cities before national launch

---

## 🛠️ Technologies Used

- **Frontend:** React Native, PWA
- **Backend:** Node.js, Firebase Functions
- **Feature Flags:** LaunchDarkly (internal)
- **Analytics:** Segment, Clevertap, PostHog
- **Courier Ops:** Internal delivery app SDK

---

## 📈 Key Outcomes

| Metric                               | Result        |
|-------------------------------------|---------------|
| COD success rate                    | ⬆️ 5 pp       |
| 30-day retention (COD users)        | ⬆️ 20%        |
| Failed courier trips                | ⬇️ 17%        |
| Ops escalations (fraud/rejects)     | ⬇️ 28%        |

Redesign improved both customer trust and operational efficiency. Courier feedback scores also rose after rollout.

---

## 🔄 Long-Term Impact

- Flow became part of default checkout UX across 3 payment types
- Courier fail-safe adopted into all delivery modes (COD, card, POS)
- Reduced fraud risk on high-volume days (e.g., holidays, promos)

---

## 📎 License

This write-up is for case study purposes only. Screens and systems shown are generalized; no user PII or proprietary flows disclosed.
