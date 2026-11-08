---
title: "Welcome offer grew bookings by 69%"
date: 2026-09-01T00:07:07+07:00
description: 4 months of A/B tests that made the offer more effective
image: /images/fm-abwelcome.png
caption:
categories:
  - fitmost
tags:
  - Product
  - UX
  - Metabase
  - Product
  - Design
  - Analytics
draft: false
---

## Context

Fitmost is a service for booking sports classes, beauty and wellness treatments in a couple of clicks. New users are shown a welcome offer at sign-up: a 500₽ discount on their first booking.

**My role:** I formulated hypotheses and designed the interface solutions for each iteration. I collected metrics together with the product manager, the A/B tests were run by an analyst.

## Objective

The overall goal is to raise C1 (conversion from sign-up to first booking). The starting point was the welcome offer: more than half of new users activated it, but not that many went on to actually book and attend. Over four months (April–August) the offer mechanics were changed four times, each time testing a new hypothesis.

The key test metric is **visit CR** (not booking, but actually showing up to the class): it shows whether the offer helps retain the user or just "pumps up" free bookings that then never happen. 

---

### Iteration 0 · Crediting the balance

**Hypothesis:** if we give the user real money on their in-app balance, they will spend it at the first opportunity.

This is the default **solution**, and the mechanic for the control group: at sign-up, 500₽ in bonuses is credited to the account — they could be used to pay for any booking in part or in full. The main funnel screens looked like this:

![image](/images/fm-abwelcome-0.png)

**What the research showed:** in qualitative interviews, users said they could see the amount on their balance but kept it "in reserve" instead of spending it right away — the bonuses expired unused. On top of that, the discount itself wasn't visible in advance: people only found out they'd pay less at checkout.

**Conclusion:** the balance mechanic creates no urgency and isn't visible at the moment of choosing a class — the benefit needs to be moved to where the user makes the decision.

---

### Iteration 1 · Discount on the booking

**Hypothesis:** if we show the discount right in the schedule (a crossed-out price), and not only at checkout, the user will see the benefit earlier and that will nudge them to book.

**Solution:** we replaced the balance credit with a direct −500 ₽ discount, visible already in the slot list and on the service screen — next to the original price, with the new price shown right beside it, and an activated promo code at checkout

![image](/images/fm-abwelcome-1.png)

**Conclusion:** a benefit that's visible at the moment of choice works better than "invisible" money on an account. 

**Result:** Conversion to first booking **+16.1%**

---

### Iteration 2 · The timer should trigger FOMO

**Hypothesis:** if the timer counts down not the "time to use the offer" but the "time until the discount itself expires", the feeling of loss will be sharper and that will nudge people to book.

**Solution:** we changed the timer's duration: besides the activation limit, we added an expiry period for the discount itself. Before, it showed the deadline for using the welcome offer as a whole; now it also shows the deadline after which the already-credited discount burns. We also changed how the price is displayed on the service screen – the benefit and the size of the discount are now clearly readable

![image](/images/fm-abwelcome-2.png)

**Conclusion:** reframing the same interface element around fear of losing money rather than fear of losing an opportunity, plus showing the benefit explicitly, is a cheap change with a noticeable effect on the perception of urgency.

**Result:** Conversion to first booking **+39.0%**

---

### Iteration 3 · Auto-activation of the offer

**Hypothesis:** if we remove the manual activation step, more users will see discounted prices without an extra click (activation conversion is ≈70% – a third of users see prices without the welcome discount) — this will add motivation to book.

**Solution:** the discount is activated automatically right after sign-up, the "Activate discount" step is removed, and we simply show that it's there.

![image](/images/fm-abwelcome-3.png)

**Result:** +4.8% in first-booking CR relative to the previous version. The version is in production, but it causes losses among those who could have booked without the offer – we need to roll back to the previous iteration.

### Summary

Each iteration responded to a specific signal from users or to a hypothesis: from "money on the balance doesn't work as an incentive" to "let's remove the extra click — they'll see the discount sooner". The final version gave **+69.1%** to first-booking conversion compared to the first.
