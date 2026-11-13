---
name: spreadsheet-rows-to-web-form
description: Fill in a web form once for every row of a spreadsheet, stopping before submit so the first row can be checked. Use when someone has many rows to enter into the same form.
---

# Spreadsheet rows to web form

This job runs on the user's own MyClawn cloud computer: a real browser that stays signed in, its own email address and files. It can outlast the chat and comes back with the answer, a screenshot of the final screen and a link to a screen recording.

## Setup

The user must have the MyClawn Computer connector signed in. If it is not, follow the setup in the cloud-computer-task skill of this repository and let the user do the sign-in; do not create accounts for them.

## Task

Hand this task to the connector's task tool, in the user's own words. The job page gives this example:

> I am sending you a spreadsheet with 20 rows of name, email and company. Open <form URL> and fill the form for each row, using the matching fields. Do the first row and stop before submitting so I can check it.

Replace the placeholders and the example values with the user's own. Show the final wording to the user before sending anything that submits a form, books something or writes to a third party.

## Steps

1. The job page says: “You send the spreadsheet and the form address.” Write the task with the goal, the sites, what the result must look like and what must not be done.
2. Send it with the connector's task tool and wait for the result.
3. What the computer does, as the job page describes it:
   - It maps the columns to the form fields and fills the first row so you can check it on the live screen.
   - It carries on with the rest; you choose whether it submits each one or stops before submitting.
4. Report the answer, the screenshot and the recording link.

## Limits

- Anything that submits in your name is yours to confirm. By default it stops before submitting.
- A CAPTCHA on the form is yours to solve on the live screen.
- Forms that reject automated entries may stop it; start with a few rows.

Full description of this job, with the steps and the limits: https://www.myclawn.com/fill-a-web-form-for-every-row-of-a-spreadsheet?utm_source=agent-skills&utm_medium=skill&utm_campaign=spreadsheet-rows-to-web-form
