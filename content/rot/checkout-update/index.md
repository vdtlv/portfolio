---
title: "Checkout update"
date: 2021-09-01T00:03:07+07:00
description: Optimized checkout process reduces abandoned carts and boosts orders for Right on Trek
image: /images/rot-ch.png
caption: 
categories:
  - Right on Trek
tags:
  - UI
  - UX
  - Product
  - Design
  - Analytics
params:
  project: 
draft: false
---

At Right on Trek I wanted to provide a comfortable and accessible user experience for new hikers and lifelong mountaineers to make their outdoor adventures as epic as possible. I was working on various parts of the service from authorization to the gear rental system. Developed CJM and user flows to turn RoT into a subscription-only platform smoothly.

I have only one of the cases below for now. Others will be added later.

![image](/images/rot-ch-0.png)

## Checkout update

### Problem
We got a big amount of abandoned carts. Depending on UX research results I found out that there are two main reasons: too many non-obvious steps during checkout and hard forms without presaved information for authorized users.

### Goal
Decrease the number of abandoned carts in relation to paid orders. Increase the number of orders through the website.

### Execution Checklist
- Find out the needs and pains of users and determine the tasks to achieve results by changing metrics together with the project manager.
- Explore the best options for implementing the payment process, study the existing customer journey, prepare hypotheses and present them to the team.
- Prepare prototypes for testing hypotheses, test and make changes based on test results.

### Results
The calendar turned into the new component with options for year/month selector, become more convenient for users of mobile devices. Updated product card for cart, now they are more informative. New option buttons added to the design system.

![image](/images/rot-ch-1.png)

In the course of work, several checkout layouts were prepared and the user path was redesigned to achieve better performance in usability tests. The final result (for a certain audience of users) has become better compared to the implemented one:

|           | Old Checkout | Updated Checkout | Result         |
|-----------|--------------|------------------|----------------|
| Success   |        58.5% |            84.2% |         +25.7% |
| Error     |        36.4% |             8.9% |         -27.5% |
| Mean time |     1:34 min |         0:20 min | ≈ 1 min faster |
| Misclicks |          20% |               6% |           -14% |

*The data is the result of testing with the Marvel app (3 weeks). It looks great, but the results of Google Analytics (1 month after implementation) came out a little different: the number of orders increased, but the number of abandoned carts did not change. After reviewing the problem, I found out that the most of the carts are left by users who do not want to create an account for the purchase. The service is turning into membership only platform so it is iportant to inform users about this or make a guest checkout.*

![image](/images/rot-ch-2.png)
![image](/images/rot-ch-3.png)