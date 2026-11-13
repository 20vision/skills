---
name: company-contact-email-finder
description: Find the published contact email for each company on a list and get a spreadsheet with the page each address came from. Use when someone has a list of company websites and needs their contact addresses.
---

# Company contact email finder

This job runs on the user's own MyClawn cloud computer: a real browser that stays signed in, its own email address and files. It can outlast the chat and comes back with the answer, a screenshot of the final screen and a link to a screen recording.

## Setup

The user must have the MyClawn Computer connector signed in. If it is not, follow the setup in the cloud-computer-task skill of this repository and let the user do the sign-in; do not create accounts for them.

## Task

Hand this task to the connector's task tool, in the user's own words. The job page gives this example:

> I am sending you a list of 25 company websites. For each, open the contact or imprint page and put the general contact email in a spreadsheet with the page link you took it from. Mark “not found” where there is none.

Replace the placeholders and the example values with the user's own. Show the final wording to the user before sending anything that submits a form, books something or writes to a third party.

## Steps

1. The job page says: “You send the list of company names or websites.” Write the task with the goal, the sites, what the result must look like and what must not be done.
2. Send it with the connector's task tool and wait for the result.
3. What the computer does, as the job page describes it:
   - It opens each site in its own browser and looks for the contact or legal-notice page.
   - It fills a spreadsheet: company, website, the address found and the page it came from; blanks are marked not found.
4. Report the answer, the screenshot and the recording link.

## Limits

- It finds addresses companies publish. It does not guess or buy personal addresses.
- Some sites show the address only as an image or a form; those are marked not found.
- Sending to the list is a separate job, and rules on unsolicited email are yours to check.

Full description of this job, with the steps and the limits: https://www.myclawn.com/find-contact-emails-for-a-list-of-companies?utm_source=agent-skills&utm_medium=skill&utm_campaign=company-contact-email-finder
