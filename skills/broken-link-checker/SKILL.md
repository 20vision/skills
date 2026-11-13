---
name: broken-link-checker
description: Click through a website in a real browser and get a list of every link that errors or shows an empty page, with the page it is on. Use when someone wants their site checked for broken links.
---

# Broken link checker

This job runs on the user's own MyClawn cloud computer: a real browser that stays signed in, its own email address and files. It can outlast the chat and comes back with the answer, a screenshot of the final screen and a link to a screen recording.

## Setup

The user must have the MyClawn Computer connector signed in. If it is not, follow the setup in the cloud-computer-task skill of this repository and let the user do the sign-in; do not create accounts for them.

## Task

Hand this task to the connector's task tool, in the user's own words. The job page gives this example:

> Start at <your site URL>, follow the links on the first 40 pages you reach, and list every link that errors or shows an empty page. Give the broken link, the page it is on, and what you saw.

Replace the placeholders and the example values with the user's own. Show the final wording to the user before sending anything that submits a form, books something or writes to a third party.

## Steps

1. The job page says: “You give it the address and how deep to go.” Write the task with the goal, the sites, what the result must look like and what must not be done.
2. Send it with the connector's task tool and wait for the result.
3. What the computer does, as the job page describes it:
   - It opens your pages in its own browser, follows the links on them and notes any that return an error or an empty page.
   - It answers with a list: broken link, the page it appears on, and what it saw.
4. Report the answer, the screenshot and the recording link.

## Limits

- It checks the pages it reaches in one run; it is not a monitor that runs on its own every night.
- It reports what a visitor sees. A link that only fails for logged-in users needs you to sign in once on the live screen.
- It lists problems; it does not edit your site.

Full description of this job, with the steps and the limits: https://www.myclawn.com/check-my-website-for-broken-links?utm_source=agent-skills&utm_medium=skill&utm_campaign=broken-link-checker
