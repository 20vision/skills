---
name: company-meeting-briefing
description: Read a company's site, news and public profiles and get a one-page briefing with every fact linked and three questions to ask. Use when someone has a meeting with a company and needs a briefing.
---

# Company meeting briefing

This job runs on the user's own MyClawn cloud computer: a real browser that stays signed in, its own email address and files. It can outlast the chat and comes back with the answer, a screenshot of the final screen and a link to a screen recording.

## Setup

The user must have the MyClawn Computer connector signed in. If it is not, follow the setup in the cloud-computer-task skill of this repository and let the user do the sign-in; do not create accounts for them.

## Task

Hand this task to the connector's task tool, in the user's own words. The job page gives this example:

> I have a meeting with <company> on Thursday about a partnership. Read their website, recent news and public profiles. Write a one-page briefing: what they do, team size if stated, recent news, and three questions I could ask. Link every fact.

Replace the placeholders and the example values with the user's own. Show the final wording to the user before sending anything that submits a form, books something or writes to a third party.

## Steps

1. The job page says: “You name the company and what the meeting is about.” Write the task with the goal, the sites, what the result must look like and what must not be done.
2. Send it with the connector's task tool and wait for the result.
3. What the computer does, as the job page describes it:
   - It opens the company’s site, its news and public profiles in its own browser and notes the facts it finds.
   - It answers with a one-page briefing: what they do, size if stated, recent news, and three questions to ask, each fact with its link.
4. Report the answer, the screenshot and the recording link.

## Limits

- It reads public pages. Private details and paywalled profiles stay out unless you sign in once on the live screen.
- A fact without a link is not stated; where it found nothing, it says so.
- Check anything important before the meeting.

Full description of this job, with the steps and the limits: https://www.myclawn.com/research-a-company-before-a-meeting?utm_source=agent-skills&utm_medium=skill&utm_campaign=company-meeting-briefing
