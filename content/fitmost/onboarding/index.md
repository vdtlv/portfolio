---
title: "The way we emphasize the advantages of service"
date: 2024-12-01T00:07:07+07:00
description: Boosting conversions with onboarding made with Lottie, another onboarding and in-app stories
image: /images/fm-onb.png
caption:
categories:
  - fitmost
tags:
  - UX
  - Product
  - Design
  - Analytics
draft: false
---

## The Challenge
Fitmost is a subscription-based service that offers access to gyms, studios, and wellness providers through a points system. However, this model confused users — they didn’t understand that the subscription was actually a flexible deposit system. This friction resulted in low conversion rates from registration to the first purchase.

Our goal was to clarify the value proposition early in the user journey and increase the conversion rate from signup to paid usage.

## User Research Insights
In early 2023, our product team conducted in-depth audience research to identify friction points and segment users. From qualitative interviews, we uncovered that users:

- Struggled to understand the point system behind the subscription.
- Didn’t see clear financial advantages over paying for individual sessions directly.
- Missed the benefits of using Fitmost for booking — flexibility, variety, convenience.

Although these benefits were mentioned in ads, they weren’t effectively communicated inside the app — particularly during the onboarding experience.

![image](/images/fm-onb-0.png)

## Solution 1: Reimagining Onboarding
Despite a high download-to-registration conversion rate, users were often left confused after signing up. The app took them straight to pricing plans without properly explaining the value.

We hypothesized that an onboarding flow could clarify the model and highlight Fitmost’s advantages, but we had two constraints:

Risk to conversion: A poor onboarding experience might reduce registrations.
Engagement: Users tend to skip onboarding screens quickly.

### First Onboarding Version

We created a short, visually striking video to explain the concept.

{{< media/video src="/images/onboarding-1.mp4" type="video/mp4" loop="true" muted="true" autoplay="true" controls="false">}}

It was eye-catching but lacked depth. We skipped user validation to launch a fast A/B test and see how onboarding affected metrics.

> 💡 But the process of creating this lottie animation and the implementation was extremely interesting: I'll write an article about this journey once!

![image](/images/fm-onb-1.png)

#### Result:

- No negative impact on registration rate — a positive sign.
- No statistically significant lift in purchase conversions. Still, this test validated that onboarding could be safely introduced.

### Second Onboarding Version

Based on follow-up user testing, we focused the second version on job stories — specific use cases like “trying new studios nearby” or “training with flexibility.”

We also added a job story block to reinforce the message even after onboarding — a lightweight solution that didn’t require deep development.

{{< media/video src="/images/onboarding-2.mp4" type="video/mp4" loop="true" muted="true" autoplay="true" controls="false" caption="Second onboarding">}}

> [add more: how these job stories were presented visually, and how users responded to them]

## Solution 2: Surfacing Subscription Value Throughout the Experience

Our research showed that users without a subscription rarely visited the home screen. Instead, they explored the **Places tab**, checking out studios and schedules.

To better understand these flows, we partnered with analysts and used Celonis, a process mining tool, to map user journeys.

![image](/images/fm-onb-2.png)

### Key Finding:

The majority of new users passed through:

- Places tab
- Activities tab
- Studio schedules

This insight helped us decide where to surface messaging about the benefits of a subscription.

We placed contextual reminders and value props on studio and schedule screens, where users were most engaged.

![image](/images/fm-onb-5.png)

![image](/images/fm-onb-3.png)

![image](/images/fm-onb-4.png)
[add more examples/screens of how messaging was implemented and its tone/visual style]

## Outcome & Impact
These changes led to an increase in conversion rates, especially among users who had previously bounced after registration.

> [add more: specific metrics — even directional ones like “+X% lift in first purchase among users who saw onboarding” would help + any feedback from users or internal stakeholders]

## Learnings
Messaging matters: Even when a product delivers value, users won’t see it without clear communication.
Testing over assumption: Launching quickly and testing iteratively gave us confidence and helped avoid overengineering.
Right message, right moment: Surfacing benefits where users are naturally browsing (not just at onboarding) was key to improving conversion.
more about celonis

## Next Steps
Expand contextual messaging throughout more flows like booking and cancellation.
Personalize onboarding further based on user intent or location.
[add more: anything in progress or backlog]