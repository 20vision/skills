---
name: product-reviews-summary
description: Read recent reviews of a product on several sites and get a short summary of praise and complaints, each with its source link. Use when someone wants to know what buyers say about a product.
---

# Product reviews summary

This job runs on the user's own MyClawn cloud computer: a real browser that stays signed in, its own email address and files. It can outlast the chat and comes back with the answer, a screenshot of the final screen and a link to a screen recording.

## Setup

The user must have the MyClawn Computer connector signed in. If it is not, follow the setup in the cloud-computer-task skill of this repository and let the user do the sign-in; do not create accounts for them.

## Task

Hand this task to the connector's task tool, in the user's own words. The job page gives this example:

> Read the recent reviews of the Sony WH-1000XM5 headphones on Amazon, Best Buy and Rtings. Summarize what buyers praise and what they complain about most, with a link for each point.

Replace the placeholders and the example values with the user's own. Show the final wording to the user before sending anything that submits a form, books something or writes to a third party.

## Steps

1. The job page says: “You name the product and the sites to check.” Write the task with the goal, the sites, what the result must look like and what must not be done.
2. Send it with the connector's task tool and wait for the result.
3. What the computer does, as the job page describes it:
   - It opens the review section on each site, reads the newest reviews and the lowest-rated ones, and notes the points that repeat.
   - It answers with a short summary of praise and complaints, each with the link it came from.
4. Report the answer, the screenshot and the recording link.

## Limits

- It reads reviews that are public. Reviews behind a login are yours to open once by taking over the screen.
- A summary is a reading of the sample it saw, not a statistic over every review; it says how many it read.
- It does not post or rate anything.

Full description of this job, with the steps and the limits: https://www.myclawn.com/collect-reviews-of-a-product-from-several-sites?utm_source=agent-skills&utm_medium=skill&utm_campaign=product-reviews-summary
