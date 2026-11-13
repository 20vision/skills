---
name: supplier-invoices-to-spreadsheet
description: Download the invoices of a period from a supplier portal and get a sheet of date, number, amount and file name with the total. Use when someone needs their invoices collected from a portal.
---

# Supplier invoices to spreadsheet

This job runs on the user's own MyClawn cloud computer: a real browser that stays signed in, its own email address and files. It can outlast the chat and comes back with the answer, a screenshot of the final screen and a link to a screen recording.

## Setup

The user must have the MyClawn Computer connector signed in. If it is not, follow the setup in the cloud-computer-task skill of this repository and let the user do the sign-in; do not create accounts for them.

## Task

Hand this task to the connector's task tool, in the user's own words. The job page gives this example:

> Open the billing page of <supplier portal> — I will take over to sign in — then download every invoice from last quarter. Put date, invoice number, amount and file name into a spreadsheet, and tell me the total.

Replace the placeholders and the example values with the user's own. Show the final wording to the user before sending anything that submits a form, books something or writes to a third party.

## Steps

1. The job page says: “You name the portal and the period.” Write the task with the goal, the sites, what the result must look like and what must not be done.
2. Send it with the connector's task tool and wait for the result.
3. What the computer does, as the job page describes it:
   - It opens the portal; you take over the live screen once to sign in, then hand back.
   - It downloads each invoice from the period and fills a sheet with date, number, amount and file name.
4. Report the answer, the screenshot and the recording link.

## Limits

- The login and any two-factor code are yours: you type them on the live screen. The password never goes to the agent.
- It downloads what the portal shows. It does not file taxes or book anything in your accounting.
- Check the total against the portal before you rely on it.

Full description of this job, with the steps and the limits: https://www.myclawn.com/download-invoices-from-supplier-portals?utm_source=agent-skills&utm_medium=skill&utm_campaign=supplier-invoices-to-spreadsheet
