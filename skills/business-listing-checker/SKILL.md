---
name: business-listing-checker
description: Check a business's listing on several directories against the correct details and get a table of what differs and where no listing exists. Use when someone wants their listings checked for wrong details.
---

# Business listing checker

This job runs on the user's own MyClawn cloud computer: a real browser that stays signed in, its own email address and files. It can outlast the chat and comes back with the answer, a screenshot of the final screen and a link to a screen recording.

## Setup

The user must have the MyClawn Computer connector signed in. If it is not, follow the setup in the cloud-computer-task skill of this repository and let the user do the sign-in; do not create accounts for them.

## Task

Hand this task to the connector's task tool, in the user's own words. The job page gives this example:

> My business is Harbor Bakery, 12 Main Street, Portland, phone 555-0142, open Tue–Sun 7–15. Check Google Maps, Yelp, Bing Places and Yellow Pages. For each, give the link and list anything that differs. Mark where there is no listing.

Replace the placeholders and the example values with the user's own. Show the final wording to the user before sending anything that submits a form, books something or writes to a third party.

## Steps

1. The job page says: “You give it the correct details and the directories.” Write the task with the goal, the sites, what the result must look like and what must not be done.
2. Send it with the connector's task tool and wait for the result.
3. What the computer does, as the job page describes it:
   - It searches each directory in its own browser and opens your listing.
   - It answers with a table: directory, link, and what differs from your details; missing listings are marked.
4. Report the answer, the screenshot and the recording link.

## Limits

- It reports differences. Changing a listing needs the owner’s login, which you hold; it does not claim or edit listings.
- A duplicate listing may be found under a slightly different name; it shows what it matched on.
- It checks the directories you name.

Full description of this job, with the steps and the limits: https://www.myclawn.com/check-my-business-listing-across-directories?utm_source=agent-skills&utm_medium=skill&utm_campaign=business-listing-checker
