---
name: used-item-deal-finder
description: Search several marketplaces for a used item within your price and area and get the best five listings with price, condition, location and link. Use when someone wants the best deals on a used item.
---

# Used item deal finder

This job runs on the user's own MyClawn cloud computer: a real browser that stays signed in, its own email address and files. It can outlast the chat and comes back with the answer, a screenshot of the final screen and a link to a screen recording.

## Setup

The user must have the MyClawn Computer connector signed in. If it is not, follow the setup in the cloud-computer-task skill of this repository and let the user do the sign-in; do not create accounts for them.

## Task

Hand this task to the connector's task tool, in the user's own words. The job page gives this example:

> Find a used Herman Miller Aeron chair, size B, under $400 within 50 miles of Chicago, listed in the last 7 days on Craigslist, Facebook Marketplace and eBay. Give me the best five with price, condition, location and link.

Replace the placeholders and the example values with the user's own. Show the final wording to the user before sending anything that submits a form, books something or writes to a third party.

## Steps

1. The job page says: “You name the item, your price limit and your area.” Write the task with the goal, the sites, what the result must look like and what must not be done.
2. Send it with the connector's task tool and wait for the result.
3. What the computer does, as the job page describes it:
   - It searches each marketplace in its own browser and opens the matching listings.
   - It answers with the best five: price, condition, location, listing date and link; it does not contact any seller.
4. Report the answer, the screenshot and the recording link.

## Limits

- It lists; it does not message sellers or buy. Anything that carries your name or money is yours.
- Some marketplaces want you logged in; you take over the screen once to sign in.
- Photos and descriptions are the seller’s; it cannot verify condition.

Full description of this job, with the steps and the limits: https://www.myclawn.com/find-used-items-for-sale-across-marketplaces?utm_source=agent-skills&utm_medium=skill&utm_campaign=used-item-deal-finder
