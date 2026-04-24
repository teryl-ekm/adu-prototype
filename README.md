# ADU Plan Review — OBC Canned Comments Tool

A simple, single-page web app that helps Ontario plan examiners and designers
work through the Ontario Building Code (OBC) canned comments for Accessory
Dwelling Unit (ADU) projects.

Built from the source spreadsheet `ADU_Interactive_Canned_Comments_Checklist_v2.xlsx`.

## How it works

1. **Project Setup** — Answer a few questions about the project (basement
   apartment / detached / addition, walkout, building age, dwelling units,
   bedrooms, etc.).
2. **Checklist** — Browse the 49 canned comments organised either by
   category or by OBC reference. Items most likely to apply are highlighted
   based on your setup answers. Tick what applies, optionally override the
   wording.
3. **Output** — A numbered list formatted as
   `Per OBC 2024 [Reference] - [Comment]`, ready to copy into a permit
   portal or download as a Word document.

## Local use

This is a single static HTML file. Just open `index.html` in any modern browser
— no install, no internet, no build step.

## Deployment

Hosted on Cloudflare Pages at
[adu-prototype.electrickitemedia.com](https://adu-prototype.electrickitemedia.com).

## Stack

- Vanilla HTML / CSS / JS — no framework, no dependencies
- Cloudflare Pages for hosting
