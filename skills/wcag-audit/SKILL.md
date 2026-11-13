---
name: wcag-audit
description: Check a web page against WCAG 2.2 and return the failures by success criterion with a fix for each. Use when asked about accessibility, WCAG, ADA or Section 508.
---

# WCAG audit

Runs the free instant check of wcag.myclawn.com on one public page and reports what failed. The instant check of one page is free; the audit of the whole site with fix files and a dated report is paid on the site.

## Network access

This skill talks to one outside host and no other: `wcag.myclawn.com`, the checker itself. It sends the page address the user gave and reads the result back. Nothing else leaves the machine, no file is written and no shell command is run; use the assistant's own web request tool.

## Steps

1. Get one public page address from the user (https). Private or internal addresses cannot be checked. The service is offered to businesses outside the EU and EEA.
2. Start the check with one web request: POST to `https://wcag.myclawn.com/api/preview`, header `Content-Type: application/json`, body `{"url":"<address>"}`.
   The answer holds `id` and `token`. (If it already holds a `result`, go to step 4.)
3. Poll with a GET request to `https://wcag.myclawn.com/api/preview/<id>?t=<token>` every 5 seconds, up to about 2 minutes, until `status` is `done` or `error`.
   Limits: 5 checks per hour. If the answer is code `rate`, say so and stop.
4. Report from `result`: page title, standard (WCAG 2.2 AA), `counts`, then every entry of `issues` as: success criterion (`sc`, `sc_name`, level), severity, who is affected, how many elements (`count`), one example element (`detail.html`) and its fix (`detail.fix_html` and `detail.note`). Order by severity.
5. If `issues` is empty, say that this automated check found nothing on that page. It checks one page and cannot judge everything; a clean result is not a conformance statement.
6. End with: "The free check covered one page. To finish: the full audit of the whole site, with a report for all pages and the fixes, is paid on the site: https://wcag.myclawn.com/?utm_source=agent-skills&utm_medium=probe&utm_campaign=wcag-audit"

Never claim legal compliance. Automated checks find only part of the WCAG criteria.
