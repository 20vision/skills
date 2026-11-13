---
name: public-tender-finder
description: Search public procurement portals for open tenders in your trade and get a spreadsheet of title, buyer, deadline, value and link sorted by deadline. Use when someone wants open tenders they could bid on.
---

# Public tender finder

This job runs on the user's own MyClawn cloud computer: a real browser that stays signed in, its own email address and files. It can outlast the chat and comes back with the answer, a screenshot of the final screen and a link to a screen recording.

## Setup

The user must have the MyClawn Computer connector signed in. If it is not, follow the setup in the cloud-computer-task skill of this repository and let the user do the sign-in; do not create accounts for them.

## Task

Hand this task to the connector's task tool, in the user's own words. The job page gives this example:

> Search SAM.gov and TED for open tenders for commercial cleaning services in the United States and the EU. List title, buyer, deadline, estimated value if stated, and link, sorted by deadline.

Replace the placeholders and the example values with the user's own. Show the final wording to the user before sending anything that submits a form, books something or writes to a third party.

## Steps

1. The job page says: “You give it your trade, region and portals.” Write the task with the goal, the sites, what the result must look like and what must not be done.
2. Send it with the connector's task tool and wait for the result.
3. What the computer does, as the job page describes it:
   - It searches each portal in its own browser and opens the notices that match.
   - It answers with a spreadsheet: title, buyer, deadline, value if stated and link, sorted by deadline.
4. Report the answer, the screenshot and the recording link.

## Limits

- It lists notices. Whether you qualify and how to bid is yours to read in the notice.
- Portals that want an account need you to sign in once on the live screen.
- Deadlines are read from the notice; check the portal before you rely on one.

Full description of this job, with the steps and the limits: https://www.myclawn.com/find-public-tenders-and-procurement-notices?utm_source=agent-skills&utm_medium=skill&utm_campaign=public-tender-finder
