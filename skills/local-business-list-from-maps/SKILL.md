---
name: local-business-list-from-maps
description: Search a map for a type of business in an area and get a spreadsheet of name, address, phone, website and rating. Use when someone wants a list of local businesses.
---

# Local business list from maps

This job runs on the user's own MyClawn cloud computer: a real browser that stays signed in, its own email address and files. It can outlast the chat and comes back with the answer, a screenshot of the final screen and a link to a screen recording.

## Setup

The user must have the MyClawn Computer connector signed in. If it is not, follow the setup in the cloud-computer-task skill of this repository and let the user do the sign-in; do not create accounts for them.

## Task

Hand this task to the connector's task tool, in the user's own words. The job page gives this example:

> Search Google Maps for dental clinics in Austin, Texas. For the first 40 results put name, address, phone, website and rating into a spreadsheet, and tell me how many you collected.

Replace the placeholders and the example values with the user's own. Show the final wording to the user before sending anything that submits a form, books something or writes to a third party.

## Steps

1. The job page says: “You name the business type and the area.” Write the task with the goal, the sites, what the result must look like and what must not be done.
2. Send it with the connector's task tool and wait for the result.
3. What the computer does, as the job page describes it:
   - It searches in its own browser and opens each business listing.
   - It fills a spreadsheet with name, address, phone, website and rating, and tells you how many it found.
4. Report the answer, the screenshot and the recording link.

## Limits

- It reads what the listing shows to a visitor; missing fields stay blank.
- A map shows a limited number of results per search; for a wider area, name several neighborhoods.
- Check the map site’s terms before you reuse its data.

Full description of this job, with the steps and the limits: https://www.myclawn.com/build-a-list-of-local-businesses-from-google-maps?utm_source=agent-skills&utm_medium=skill&utm_campaign=local-business-list-from-maps
