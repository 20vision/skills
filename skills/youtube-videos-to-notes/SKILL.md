---
name: youtube-videos-to-notes
description: Turn YouTube videos into notes with key points and timestamps, read from each video's transcript. Use when someone wants the key points of videos without watching them.
---

# YouTube videos to notes

This job runs on the user's own MyClawn cloud computer: a real browser that stays signed in, its own email address and files. It can outlast the chat and comes back with the answer, a screenshot of the final screen and a link to a screen recording.

## Setup

The user must have the MyClawn Computer connector signed in. If it is not, follow the setup in the cloud-computer-task skill of this repository and let the user do the sign-in; do not create accounts for them.

## Task

Hand this task to the connector's task tool, in the user's own words. The job page gives this example:

> Open these three videos: <link 1>, <link 2>, <link 3>. For each, write five key points with the timestamp where it is said, and one line on who it is for.

Replace the placeholders and the example values with the user's own. Show the final wording to the user before sending anything that submits a form, books something or writes to a third party.

## Steps

1. The job page says: “You paste the video links or name a channel and a count.” Write the task with the goal, the sites, what the result must look like and what must not be done.
2. Send it with the connector's task tool and wait for the result.
3. What the computer does, as the job page describes it:
   - It opens each video in its own browser and reads the transcript where the video has one.
   - It answers with notes per video: key points, each with a timestamp so you can jump to it.
4. Report the answer, the screenshot and the recording link.

## Limits

- It needs a transcript or captions on the video; a video without one is reported as not readable, not guessed.
- Long videos are summarized from their transcript, not watched frame by frame; anything shown only on screen can be missed.
- It does not download or republish the videos.

Full description of this job, with the steps and the limits: https://www.myclawn.com/summarize-youtube-videos-into-notes?utm_source=agent-skills&utm_medium=skill&utm_campaign=youtube-videos-to-notes
