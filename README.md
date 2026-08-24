# Gina Turns 40 — RSVP Website v7

This version includes post-RSVP calendar saving.

## Calendar behavior

When a guest answers **Yes** and submits the RSVP, the confirmation area shows:

- **Google Calendar** — opens a pre-filled Google Calendar event. The guest presses Save.
- **Apple / Outlook / other** — opens/downloads `gina-40-birthday.ics`.

Event details:
- Saturday, 19 September 2026
- 20:00–00:00
- Zaimi 45, Glyka Nera, Greece
- `.ics` reminder: 1 day before

A website cannot silently write into a guest's private Google Calendar without permission, so Google requires the guest to confirm by pressing Save.

## Upload to GitHub

Upload these files:
- `index.html`
- `gina-40-birthday.ics`
- `music.mp3`
- Gina's photo files (`gina1.jpg`, `gina2.jpg`, etc.)

`Code.gs` stays in Google Apps Script, not GitHub.
