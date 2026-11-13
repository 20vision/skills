---
name: product-listings-to-spreadsheet
description: Read every product in a store category page by page and get a spreadsheet of name, price, link and stock status. Use when someone wants a store's product listings in a spreadsheet.
---

# Product listings to spreadsheet

This job runs on the user's own MyClawn cloud computer: a real browser that stays signed in, its own email address and files. It can outlast the chat and comes back with the answer, a screenshot of the final screen and a link to a screen recording.

## Setup

The user must have the MyClawn Computer connector signed in. If it is not, follow the setup in the cloud-computer-task skill of this repository and let the user do the sign-in; do not create accounts for them.

## Task

Hand this task to the connector's task tool, in the user's own words. The job page gives this example:

> Open the “Laptops” category of <store URL>. For every product on every page, put name, price, product link and stock status into a spreadsheet. Tell me how many products you found.

Replace the placeholders and the example values with the user's own. Show the final wording to the user before sending anything that submits a form, books something or writes to a third party.

## Steps

1. The job page says: “You name the store, the category and the columns you want.” Write the task with the goal, the sites, what the result must look like and what must not be done.
2. Send it with the connector's task tool and wait for the result.
3. What the computer does, as the job page describes it:
   - It opens the category in its own browser, goes page by page, and reads each product’s name, price, link and stock note.
   - It saves a spreadsheet on its desktop and tells you when it is ready; you can watch the rows appear or ask for the file by mail.
4. Report the answer, the screenshot and the recording link.

## Limits

- It reads public pages the way a visitor does. A store that blocks automated visits or hides prices behind a login may stop it; if a login is needed you take over the screen once.
- Very large catalogs take long: a few hundred products is a sensible first run, thousands are slow.
- Check the store’s terms before you reuse its data; that call is yours.

Full description of this job, with the steps and the limits: https://www.myclawn.com/scrape-product-listings-into-a-spreadsheet?utm_source=agent-skills&utm_medium=skill&utm_campaign=product-listings-to-spreadsheet
