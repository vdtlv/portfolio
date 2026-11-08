---
title: "Pretty pictures cut churn by 16%"
date: 2026-03-01T00:07:07+07:00
description: Tweaks at the top of the funnel that help keep users focused on what matters
image: /images/fm-map-funnel.png
caption:
categories:
  - fitmost
tags:
  - UX
  - Animations
  - Amplitude
  - Lottie
  - Product
  - Design
  - AI
draft: false
---

## Контекст

Fitmost is a service for booking sports classes, beauty and wellness treatments in a couple of clicks. The map is one of the key tools for finding the right place, but new users get lost on the map because of the sheer amount of choice

![image](/images/fm-map-funnel-0.png)

Qualitative research revealed two different behavior patterns:

- **New users** open the map just to explore what's nearby. They don't have a formed intent yet and don't pick a category at this stage.
- **Users with a specific intent** go straight to search, pick a category and so narrow down the map results themselves, before browsing.

After that, both groups follow the same path: choosing a place by photo/rating → choosing a class in that place's schedule.

Product analytics pointed to the problem quantitatively: the longer a user stays on the map, the lower the chance they reach a booking. This is an observed correlation — too many results tire people out and reduce their willingness to keep choosing, but we haven't proven a direct cause-and-effect relationship.
 
## Hypothesis

I formulated the hypothesis: **if we give users a quick way to narrow the map results by category, without taking away the ability to view the map broadly, decision time will drop and the conversion to opening a place will grow.**

A key constraint I built into the solution from the start: the hypothesis must not break the flow for new users, who need exactly that broad "what's nearby" overview — narrowing has to be an **option**, not the default behavior.

## Solution

After the user picks preferences during onboarding, app shows everything relevant on the map. User can refine/change the categories visible on the screen.

![image](/images/fm-map-funnel-1.png)

I tested this solution qualitatively – the sense of how wide the choice is disappears, and saw no statistically significant quantitative changes, so decided to iterate on the map filters.

![image](/images/fm-map-funnel-2.png)

The map shows all places without pre-filtering — broad coverage is preserved by default. Users can refine categories: I added personalization and first show what they selected themselves, then suggest similar options.

*Separately, as part of the task, I reworked **end-to-end category state**: the category selected on the map is carried over to the class and studio schedule selection step, removing the need to select it again. So the solution became not just about the "map", but about the category as a single entity that lives throughout the whole journey.*

![image](/images/fm-map-funnel-3.png)

## Results

Measured by comparing periods before/after the release on a sample of users.

- Churn from the map: down from **≈35% to 29.28%** — a statistically significant change on this sample
- Transition to the place card is now: **65%** 
- Behavioral segmentation: for **new users** the hypothesis was confirmed — they became more active in choosing a category and exploring the map with the filter applied, meaning the solution didn't just narrow the results, it helped new users get oriented faster. For **active users** the metric wasn't significantly affected, since their behavior pattern was already formed.