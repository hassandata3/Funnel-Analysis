# Funnel Analysis

## Overview

How many users enter an e-commerce funnel, and how many actually complete a purchase?

This project analyzes the customer journey through four key stages:

**Browse → Add to Cart → Checkout → Purchase**

The goal was not simply to calculate conversion rates, but to identify where users are being lost, understand which areas deserve further investigation, and distinguish between what the data can prove and what requires additional evidence.

---

## Business Objective

The main objective is to understand:

- Where are users dropping off in the funnel?
- Which funnel stage has the largest loss?
- How long does it take users to move between stages?
- How does conversion differ across devices, channels, and regions?
- Which findings should be prioritized for further investigation?

---

## Key Findings

### 1. The largest drop-off occurs after Add to Cart

The largest user loss occurs between:

**Add to Cart → Checkout**

with **3,493 users** lost at this stage.

This makes the transition to Checkout the main area that requires further investigation.

### 2. No clear evidence of a transition-time problem

The average transition times are relatively close:

- Browse → Cart: **3.50 min**
- Cart → Checkout: **3.48 min**
- Checkout → Purchase: **3.42 min**

Therefore, the current data does not indicate a clear transition-time issue that should be treated as the top priority.

### 3. Mobile has the lowest conversion

Conversion by device:

- Desktop: **10.58%**
- Tablet: **10.06%**
- Mobile: **9.47%**

Mobile has the lowest conversion rate, but the difference is relatively limited compared with the much larger drop-off observed between Add to Cart and Checkout.

Therefore, it is treated as a secondary finding rather than the primary problem.

### 4. Overall funnel performance

- Sessions: **10,000**
- Completed purchases: **1,004**
- Overall conversion: **10.04%**
- Total revenue: **$277,323**
- Average order value: **$276.22**
- Average time to purchase: **10.4 minutes**

---

## Analytical Thinking

One of the main principles of this analysis was to avoid jumping from a finding directly to a recommendation.

The data tells us:

**WHERE** users are being lost.

But it does not necessarily tell us:

**WHY** they are being lost.

For example, the drop-off between Add to Cart and Checkout could potentially be related to different friction points such as:

- Difficulty completing the next step
- Unexpected additional charges
- Checkout friction
- Other user-experience issues

However, these cannot be confirmed from the current data alone.

Rather than assuming a cause, the appropriate next step is to investigate the user experience and collect additional behavioral or technical evidence.

Once an evidence-based hypothesis is identified, an **A/B test** can be used to validate whether a proposed change improves conversion.

---

## Recommendations / Next Steps

Based on the available data, the main next step is:

**Investigate the Add to Cart → Checkout experience.**

The purpose is to identify the underlying cause of the high drop-off before proposing a specific intervention.

Possible next steps include:

1. Analyze detailed checkout events.
2. Investigate user behavior within the checkout flow.
3. Review technical or payment-related events.
4. Identify an evidence-based hypothesis.
5. Validate the proposed change through A/B testing.

The analysis intentionally avoids making a specific recommendation without sufficient evidence.

---

## Tools

- **SQL** — Data extraction, transformation, and analysis
- **Power BI** — Data visualization and interactive reporting
