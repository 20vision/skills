---
name: company-news-brief
description: Find the last seven days of news about a company or topic and get a brief of the ten most relevant items with date and link, mailed to you. Use when someone wants this week's news on a company.
---

# Company news brief

This job runs on the user's own MyClawn cloud computer: a real browser that stays signed in, its own email address and files. It can outlast the chat and comes back with the answer, a screenshot of the final screen and a link to a screen recording.

## Setup

The user must have the MyClawn Computer connector signed in. If it is not, follow the setup in the cloud-computer-task skill of this repository and let the user do the sign-in; do not create accounts for them.

## Task

Hand this task to the connector's task tool, in the user's own words. The job page gives this example:

> Find news from the last seven days about <company>. Write a brief of the ten most relevant items with headline, date, one line on why it matters, and the link. Send it to <your address>.

Replace the placeholders and the example values with the user's own. Show the final wording to the user before sending anything that submits a form, books something or writes to a third party.

## Steps

1. The job page says: “You name the company or topic and the period.” Write the task with the goal, the sites, what the result must look like and what must not be done.
2. Send it with the connector's task tool and wait for the result.
3. What the computer does, as the job page describes it:
   - It searches news sites in its own browser and opens the articles from the period.
   - It writes a short brief, each item with its headline, date and link, and mails it to you.
4. Report the answer, the screenshot and the recording link.

## Limits

- You start each brief; it does not send one by itself every week.
- Paywalled articles show only what the site shows a visitor; it says so.
- A brief is a reading of what it found, not a complete news archive.

Full description of this job, with the steps and the limits: https://www.myclawn.com/write-a-brief-of-this-weeks-news-about-a-company?utm_source=agent-skills&utm_medium=skill&utm_campaign=company-news-brief
