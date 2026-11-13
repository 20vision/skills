---
name: product-price-change-tracker
description: Save the prices and stock status of products you watch and, on the next run, get a list of what went up or down. Use when someone wants to know what changed in the prices of products they follow.
---

# Product price change tracker

This job runs on the user's own MyClawn cloud computer: a real browser that stays signed in, its own email address and files. It can outlast the chat and comes back with the answer, a screenshot of the final screen and a link to a screen recording.

## Setup

The user must have the MyClawn Computer connector signed in. If it is not, follow the setup in the cloud-computer-task skill of this repository and let the user do the sign-in; do not create accounts for them.

## Task

Hand this task to the connector's task tool, in the user's own words. The job page gives this example:

> Open these product pages: <link 1>, <link 2>, <link 3>, <link 4>. Put the product name, current price and stock status into a spreadsheet with today’s date. The next time I ask, compare with this sheet and tell me what changed.

Replace the placeholders and the example values with the user's own. Show the final wording to the user before sending anything that submits a form, books something or writes to a third party.

## Steps

1. The job page says: “You give it the product links.” Write the task with the goal, the sites, what the result must look like and what must not be done.
2. Send it with the connector's task tool and wait for the result.
3. What the computer does, as the job page describes it:
   - It opens each page in its own browser, reads the current price and stock note and saves them with today’s date in a spreadsheet.
   - On a later run you ask it again; it compares with the saved sheet and lists what went up or down.
4. Report the answer, the screenshot and the recording link.

## Limits

- You start each check: it does not watch prices on its own in the background.
- A price shown only after you choose a size, color or region needs that choice named in the prompt.
- Pages that block automated visits may stop it; a CAPTCHA is yours to clear on the live screen.

Full description of this job, with the steps and the limits: https://www.myclawn.com/track-price-changes-on-products-i-watch?utm_source=agent-skills&utm_medium=skill&utm_campaign=product-price-change-tracker
