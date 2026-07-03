# Dan Sucks Fart Button

## Status
Ready for Paperclip implementation.

## Purpose
A tiny static gag web page for Claw Labs: display the text "Dan sucks!" and provide a button that plays a fart noise.

## MVP Scope
- Single static web page.
- Big, obvious headline: `Dan sucks!`.
- Button labeled clearly enough to indicate it plays a fart noise.
- Button click plays a fart-like sound without requiring external audio assets if practical.
- Page should run locally with a simple static server.

## Out of Scope
- Deployment or public hosting.
- Backend service.
- Analytics, accounts, persistence, or external APIs.
- Paid assets or external audio downloads.

## Suggested Verification
```bash
python3 -m http.server 8123 --bind 127.0.0.1
```
Open `http://127.0.0.1:8123/`, click the button, and confirm there are no browser console errors.

## Paperclip Reference
To be filled after Paperclip issue creation.
