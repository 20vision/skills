---
name: podcast-guest-finder
description: Find active podcasts on a topic and get a spreadsheet with the latest episode date, contact or pitch page and whether the page mentions guests. Use when someone wants podcasts to pitch as a guest.
---

# Podcast guest finder

This job runs on the user's own MyClawn cloud computer: a real browser that stays signed in, its own email address and files. It can outlast the chat and comes back with the answer, a screenshot of the final screen and a link to a screen recording.

## Setup

The user must have the MyClawn Computer connector signed in. If it is not, follow the setup in the cloud-computer-task skill of this repository and let the user do the sign-in; do not create accounts for them.

## Task

Hand this task to the connector's task tool, in the user's own words. The job page gives this example:

> Find 20 active podcasts about bootstrapped software companies. For each: show name, date of the latest episode, link to its contact or guest-pitch page, and whether the page mentions guests. Spreadsheet, please.

Replace the placeholders and the example values with the user's own. Show the final wording to the user before sending anything that submits a form, books something or writes to a third party.

## Steps

1. The job page says: “You name your topic and what kind of shows you want.” Write the task with the goal, the sites, what the result must look like and what must not be done.
2. Send it with the connector's task tool and wait for the result.
3. What the computer does, as the job page describes it:
   - It searches directories in its own browser and opens each show’s page.
   - It answers with a spreadsheet: show, latest episode date, contact or pitch page, and whether it mentions guests.
4. Report the answer, the screenshot and the recording link.

## Limits

- It builds the list. Writing to the hosts is yours; it does not message anyone for you in this job.
- “Active” is judged by the date of the latest episode it saw.
- It lists what the show pages say; it cannot know who accepts pitches.

Full description of this job, with the steps and the limits: https://www.myclawn.com/find-podcasts-that-take-guests-on-my-topic?utm_source=agent-skills&utm_medium=skill&utm_campaign=podcast-guest-finder
