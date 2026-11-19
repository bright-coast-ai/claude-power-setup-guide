# Suggesting a change

Thank you for helping improve the guide. Every change goes through a pull request, and the maintainer reviews and approves it before it goes live. Whatever is on the `stable` branch is live at setup.brightcoast.ai within a few minutes, so nothing reaches `stable` without that approval.

If you use Claude Code to make the change, ask it to read this file first.

## How to suggest a change

1. If you have not been given write access to this repository, fork it first and work in your fork. Then start a new branch from `stable`, named after what you are changing, for example `suggest/chatgpt-memory-import`.
2. Make your change. Keep each pull request to one topic.
3. Open a pull request into `stable`. In the description, say what happened in a session that made you want the change, and what you changed.
4. Wait for the review. Do not merge it yourself. The maintainer may ask questions or edit it before approving.

## Leave these alone

The maintainer handles all of these when approving, so leave them unchanged:

- Version numbers and dates anywhere (the guide header, its changelog, the page stamps, `CHANGELOG.md`, `VERSION`).
- `catalog.json`, including the fingerprints.
- The scripts in `scripts/`.

## How to write

- No em dashes and no en dashes. Use commas, colons and full stops. Do not use a hyphen as a pause.
- The company is "Bright Coast AI", three words.
- Plain, warm and short. No jargon.
- This repository is public. Never include a client's or a team member's name, an email address, a phone number, a token, a password or a path from your own computer.
- Keep LF line endings.

## What setup instructions must not say

- Do not tell anyone to make a folder, save the guide into a folder, change directory, select a folder, or start Claude Code in a particular place.
- The flow stays: install Claude Code, log in, download the guide, open Claude Code, start a new session and say the one sentence that names the guide file.
- Every sentence people copy names the file, so Claude can find it.
