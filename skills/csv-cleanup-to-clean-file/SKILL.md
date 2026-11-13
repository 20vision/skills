---
name: csv-cleanup-to-clean-file
description: Clean a CSV file (duplicate rows removed by email, names capitalised) and get the cleaned file back by email. Use when someone sends a CSV that needs tidying.
---

# CSV cleanup to clean file

This job runs on the user's own MyClawn cloud computer: a real browser that stays signed in, its own email address and files. It can outlast the chat and comes back with the answer, a screenshot of the final screen and a link to a screen recording.

## Setup

The user must have the MyClawn Computer connector signed in. If it is not, follow the setup in the cloud-computer-task skill of this repository and let the user do the sign-in; do not create accounts for them.

## Task

Hand this task to the connector's task tool, in the user's own words. The job page gives this example:

> I am sending you a CSV. Remove duplicate rows by email, fix the capitalisation of names, and mail the cleaned file to <your address>.

Replace the placeholders and the example values with the user's own. Show the final wording to the user before sending anything that submits a form, books something or writes to a third party.

## Steps

1. The job page says: “You send the file with the send-file button in the app.” Write the task with the goal, the sites, what the result must look like and what must not be done.
2. Send it with the connector's task tool and wait for the result.
3. What the computer does, as the job page describes it:
   - It opens the CSV in LibreOffice on its desktop, removes duplicate rows by email and fixes the capitalisation of names.
   - It mails the cleaned file back from its own address.
4. Report the answer, the screenshot and the recording link.

## Limits

- The file goes in through the send-file button in the app, so you need an account first.
- The mail comes from the agent’s own address, not yours, and goes to the address you give it.
- Long jobs count against your plan’s rolling usage windows (5% of the monthly grant per 5 hours, 30% per week); when one is reached you are told when it resets.

Full description of this job, with the steps and the limits: https://www.myclawn.com/clean-up-a-csv-file-automatically?utm_source=agent-skills&utm_medium=skill&utm_campaign=csv-cleanup-to-clean-file
