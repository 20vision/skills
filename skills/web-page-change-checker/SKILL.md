---
name: web-page-change-checker
description: Save the wording of a web page and, on the next run, get the exact differences. Use when someone wants to know what changed on a page.
---

# Web page change checker

This job runs on the user's own MyClawn cloud computer: a real browser that stays signed in, its own email address and files. It can outlast the chat and comes back with the answer, a screenshot of the final screen and a link to a screen recording.

## Setup

The user must have the MyClawn Computer connector signed in. If it is not, follow the setup in the cloud-computer-task skill of this repository and let the user do the sign-in; do not create accounts for them.

## Task

Hand this task to the connector's task tool, in the user's own words. The job page gives this example:

> Open <page URL>, save the current wording of the section on opening hours and fees, and tell me it is saved. When I ask again, open the page and tell me exactly what changed.

Replace the placeholders and the example values with the user's own. Show the final wording to the user before sending anything that submits a form, books something or writes to a third party.

## Steps

1. The job page says: “You give it the page and what to watch for.” Write the task with the goal, the sites, what the result must look like and what must not be done.
2. Send it with the connector's task tool and wait for the result.
3. What the computer does, as the job page describes it:
   - It opens the page in its own browser and saves the relevant text with today’s date.
   - When you ask again, it opens the page, compares it with the saved version and lists the differences.
4. Report the answer, the screenshot and the recording link.

## Limits

- You start each check; it does not watch the page on its own.
- Pages that change on every load, such as ads or timers, need you to name the part to compare.
- It sees what a visitor sees; a page behind a login needs you to sign in once.

Full description of this job, with the steps and the limits: https://www.myclawn.com/check-a-web-page-for-changes?utm_source=agent-skills&utm_medium=skill&utm_campaign=web-page-change-checker
