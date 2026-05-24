# Retention Strategy Report
## D2C Customer Churn Capstone — Part 2

---

## Segment Overview

| Segment | Count | Churn Rate | Avg Spend (₹) | Priority |
|---|---|---|---|---|
| Champions | 389 | 0.0% | ₹5,938 | Maintain |
| Loyal Customers | 488 | 35.9% | ₹4,678 | Nurture |
| At-Risk High Value | 98 | 100.0% | ₹4,209 | 🔴 Urgent |
| High-Value but Unhappy | 8 | 75.0% | ₹3,857 | 🔴 Urgent |
| New Customers | 233 | 0.0% | ₹1,783 | Onboard |
| Needs Attention | 966 | 68.5% | ₹1,714 | Watch |
| Discount Sensitive | 129 | 75.2% | ₹1,554 | Re-educate |
| Dormant | 89 | 100.0% | ₹1,549 | Win-back |

*(Note: Data reflects mathematically computed values from the raw dataset, where overall churn is 47.0%)*

---

## Segment Details & Recommended Actions

### 1. Champions (Score 13-15, R≥4)
**Behaviour**: Most recent buyers, highest frequency, highest spend.
They love the brand and buy regularly without needing discounts. With 0.0% churn, they are highly reliable.

**Recommended Action**:
- Invite to VIP loyalty programme
- Early access to new product launches
- Ask for reviews and referrals (referral bonus)
- Do NOT offer discounts — unnecessary cost

**Expected Business Value**: High lifetime value. Protect at all cost.

---

### 2. Loyal Customers (Score 10-12, F≥4)
**Behaviour**: Frequent buyers with decent spend. Brand advocates who buy consistently. However, they have a 35.9% churn rate, indicating some risk if neglected.

**Recommended Action**:
- Loyalty points programme (double points on next purchase)
- Personalised "thank you" email with product recommendations
- Early access to seasonal sales

**Expected Business Value**: Likely to upsell to Champions tier with gentle nudge.

---

### 3. At-Risk High Value (M≥4, R≤2)
**Behaviour**: Previously big spenders who have gone silent. No recent order in 60-90+ days. This group has a 100.0% churn rate—if we do not act, they are gone.

**Recommended Action**:
- Personalised win-back email: "We miss you — here's 10% off"
- If no response in 7 days, escalate with a second email + free shipping
- Phone outreach for top 20% by lifetime value

**Expected Business Value**: 20-30% reactivation rate typical. High ROI per customer saved.

---

### 4. High-Value but Unhappy (M≥4, tickets≥3)
**Behaviour**: Spend a lot but have raised multiple complaints. High churn risk due to poor CX (75.0% churn rate).

**Recommended Action**:
- DO NOT start with a discount — address the complaint first
- CX team personal call or email to resolve open issues
- Once resolved, offer a goodwill gesture (free product or credit)

**Expected Business Value**: Resolving CX issues has higher retention impact than discounts.

---

### 5. New Customers (F≤2, R≥4)
**Behaviour**: Recently joined, only 1-2 orders. Still evaluating the brand, but highly engaged right now (0.0% churn).

**Recommended Action**:
- Welcome email series (3 emails over 30 days)
- Prompt second purchase with "Complete your routine" bundle offer
- Share user reviews and product education

**Expected Business Value**: Convert to Loyal Customers within 90 days.

---

### 6. Dormant (R≤2, sessions=0)
**Behaviour**: No order in 180+ days, no app activity. Largely disengaged with a 100.0% churn rate.

**Recommended Action**:
- 3-email win-back series over 3 weeks:
  - Email 1: Brand reminder + best sellers
  - Email 2: "Here's 15% off — just for you"
  - Email 3: Final offer before unsubscribing
- If no response after 3 emails, remove from active campaign lists

**Expected Business Value**: 5-10% reactivation typical. Saves money by sunsetting the rest.

---

### 7. Discount Sensitive (return_rate > 30%)
**Behaviour**: Frequent returners. Possibly buying during sales and returning items. Massive churn risk (75.2%).

**Recommended Action**:
- Avoid offering more discounts (reinforces behaviour)
- Focus on product education: "How to choose the right product"
- Highlight free samples or trial sizes instead

**Expected Business Value**: Reduce return costs; gradually increase genuine attachment.

---

### 8. Needs Attention (Mid-tier, no strong signal)
**Behaviour**: Mid-level RFM, no alarming signals but not growing either (68.5% churn rate).

**Recommended Action**:
- Monitor for 30 days before spending campaign budget
- Send product discovery email with personalised recommendations
- A/B test messaging to identify what resonates

---

## Campaign Budget Prioritization

Assume a limited monthly budget.

| Priority | Segment | Reason | Budget % |
|---|---|---|---|
| 1st | At-Risk High Value | Highest ROI per rupee spent | 35% |
| 2nd | High-Value but Unhappy | Resolve complaints = retention | 25% |
| 3rd | Dormant | Low-cost email; even 10% ROI is worth it | 20% |
| 4th | New Customers | Onboarding is cheap; LTV payoff is long | 15% |
| 5th | Champions | Just maintain; minimal spend needed | 5% |

**Do NOT spend on**: Discount Sensitive customers — more discounts worsen the problem.
