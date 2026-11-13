---
name: seo-audit-to-fix-list
description: Audit the pages of a website and get a spreadsheet with title, description, H1, broken links and what to fix for each page. Use when someone wants an on-page SEO check of their site.
---

# SEO audit to fix list

This job runs on the user's own MyClawn cloud computer: a real browser that stays signed in, its own email address and files. It can outlast the chat and comes back with the answer, a screenshot of the final screen and a link to a screen recording.

## Setup

The user must have the MyClawn Computer connector signed in. If it is not, follow the setup in the cloud-computer-task skill of this repository and let the user do the sign-in; do not create accounts for them.

## Task

Hand this task to the connector's task tool, in the user's own words. The job page gives this example:

> Audit the first 30 pages you can reach from <your site URL>. For each page note the title, meta description, H1, and whether any link on it is broken. Put it in a spreadsheet with a column “what to fix”.

Replace the placeholders and the example values with the user's own. Show the final wording to the user before sending anything that submits a form, books something or writes to a third party.

## Steps

1. The job page says: “You give it your address and how many pages to check.” Write the task with the goal, the sites, what the result must look like and what must not be done.
2. Send it with the connector's task tool and wait for the result.
3. What the computer does, as the job page describes it:
   - It opens the pages in its own browser and notes the title, description, main heading, image text and any link that fails.
   - It answers with a spreadsheet: one row per page, what is missing or too long, and what to change.
4. Report the answer, the screenshot and the recording link.

## Limits

- It is a reading of the pages it opens, not a crawler of thousands of URLs and not a rankings tool: it has no search-position or backlink data.
- Pages behind a login need you to sign in once on the live screen.
- It lists fixes; it does not change your site.

Full description of this job, with the steps and the limits: https://www.myclawn.com/run-an-seo-audit-on-my-website?utm_source=agent-skills&utm_medium=skill&utm_campaign=seo-audit-to-fix-list
